```
Algoritmo fullName
	Imprimir "Write a Name: ";
	Leer nombre;
	Imprimir "Write a Last Name: ";
	Leer apellido;
	
	nombreCorregido=Mayusculas(SubCadena(nombre,0,1)) + Minusculas(SubCadena(nombre,2,Longitud(nombre)));
	apellidoCorregido=Mayusculas(SubCadena(apellido,0,1)) + Minusculas(SubCadena(apellido,2,Longitud(apellido)));
	resultado=nombreCorregido+" "+apellidoCorregido;
	Imprimir resultado;	
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210281282-a57fdbc9-bd22-4bb2-93d6-eeb3e43586eb.png)
