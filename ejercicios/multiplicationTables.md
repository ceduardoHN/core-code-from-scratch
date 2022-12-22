```
Algoritmo multiplicationTables
	Imprimir "---- Tablas de Multiplicar ----";
	Imprimir "Ingrese la Tabla a Calcular: ";
	Leer numTabla;
	
	Imprimir "@ Tabla del ",ConvertirATexto(numTabla)," @";	
	iterador=1;
	Mientras iterador<=10 Hacer
		mul=numTabla*iterador;
		Imprimir ConvertirATexto(numTabla),"*",ConvertirATexto(iterador)," = ", ConvertirATexto(mul);
		iterador=iterador+1;
	Fin Mientras	
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/209067435-4221e169-3243-413e-adcf-25c6126042b7.png)
