```
Funcion resultado <- sumOfPairs()
	suma=0;
	bandera=Verdadero;
	Repetir
		Imprimir "Write a number between 1 and 100: ";
		Leer number;		
		Si number<0 O number>100 Entonces
			Imprimir "Invalid number.";
			Imprimir "";
			bandera=Falso;			
		SiNo
			Si num%2=0 Entonces
				suma=suma+number;
			FinSi
		Fin Si		
	Hasta Que bandera=Falso;
	resultado=Concatenar("La suma es: ",ConvertirATexto(suma));
FinFuncion

Algoritmo algoritmoSumOfPairs
	Imprimir sumOfPairs();
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210642686-82fea781-f496-4d5a-b1f8-829a8bdd5588.png)
![imagen](https://user-images.githubusercontent.com/116420679/210642773-49f11e15-b35e-4635-9fd1-1adb628335eb.png)
