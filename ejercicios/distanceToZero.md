```
Algoritmo distanceToZero
	Imprimir "Write a Number: ";
	Leer number1;
	Para i<-1 Hasta 4 Hacer
		Imprimir "Write a Number: ";
		Leer number2;
		Si abs(number2)>abs(number1) Entonces
			number1=number2;
		Fin Si
	Fin Para
	Imprimir trunc(number1);	
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210282613-53fe46ea-fd4a-4000-b087-877866e24403.png)
