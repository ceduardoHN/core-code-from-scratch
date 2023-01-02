```
Algoritmo sales
	Imprimir "Write the total number of sales to enter: ";
	Leer numVentas;
	ganancia=0;
	
	Para i<-1 Hasta numVentas Hacer
		Imprimir "Write the value of the sale number: ",i;
		Leer num;
		ganancia=ganancia+num;
	Fin Para
	
	promedio=ganancia/numVentas;
	Imprimir "";
	Imprimir "The average sales is: ",promedio;	
	Si numVentas<5 Entonces
		Imprimir "The comission received by the seller is: ",ganancia*0.10;
	SiNo
		Imprimir "The comission received by the seller is: ",ganancia*0.15;
	Fin Si
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210277364-a4ce469c-7156-4b3b-882a-9ba6bc6a07b6.png)
