```
Funcion celsius <- fahrToCelsius(fahrenheit)
	celsius=(fahrenheit-32)*(5/9);
FinFuncion

Algoritmo weatherAverage
	total=0;
	count=0;
	Repetir
		Imprimir "Select an option: ";
		Imprimir "a. Enter Degrees Celsius.";
		Imprimir "b. Enter Degrees Fahrenheit.";
		Imprimir "x. Go Out.";
		Leer option;
		Si option=="a" O option=="b" Entonces
			Leer degree;
			count=count+1;
		FinSi
		Si option=="a" Entonces
			total=total+degree;
		FinSi
		Si option=="b" Entonces
			total=total+fahrToCelsius(degree);
		FinSi
	Hasta Que option=="x";
	average=total/count;
	Imprimir average;
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210676914-3235450b-c605-404d-b50b-ea1710e59ad8.png)
