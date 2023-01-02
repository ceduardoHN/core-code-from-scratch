```
Algoritmo evenOrOdd
	Repetir
		Imprimir "Write a number between 1 and 50: ";
		Leer number;
		bandera=Verdadero;
		
		Si number>=1 Y number<=50 Entonces
			par=number%2=0;
			Para i<-1 Hasta number Con Paso 1 Hacer
				Si i%2=0 Y par Entonces
					Imprimir i;
				FinSi
				Si i%2=1 Y ~(par) Entonces
					Imprimir i;
				FinSi
			Fin Para
			bandera=Falso;
		SiNo
			Imprimir "Invalid Number";
			Imprimir "";
		Fin Si
	Hasta Que bandera=Falso;	
FinAlgoritmo
```
Número Par: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210279197-13b8acd6-b513-4405-b46f-5c04dffb9d9f.png) <br>
Número Impar: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210279223-5b911167-bc1e-4f41-9871-a877a87a8c99.png) <br>
Número Inválido: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210279272-bab73329-c346-4e75-914b-5d9188d0241e.png)
