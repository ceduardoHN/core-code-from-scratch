```
Algoritmo multiplicationTablesWithFor
	Imprimir "---- Tablas de Multiplicar ----";
	Imprimir "Ingrese la Tabla a Calcular: ";
	Leer numTabla;
	
	Imprimir "@ Tabla del ",ConvertirATexto(numTabla)," @";
	Para iterador<-1 Hasta 10 Hacer
		mul=numTabla*iterador;
		Imprimir ConvertirATexto(numTabla),"*",ConvertirATexto(iterador)," = ", ConvertirATexto(mul);
	Fin Para
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/209070126-f158e8f5-cf46-45d4-a534-c352596f14b7.png)

