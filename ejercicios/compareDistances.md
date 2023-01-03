```
Funcion resultado <- compareDistances()
	numNegativo=0;
	numPositivo=0;
	Para i<-1 Hasta 5 Hacer
		Imprimir "Write a number: ";
		Leer number;
		Si number > 0 Entonces
			numPositivo=numPositivo+number;
		SiNo
			numNegativo=numNegativo+number;
		FinSi
	Fin Para
	resultado=numPositivo>abs(numNegativo);
FinFuncion

Algoritmo algoritmoCompareDistances
	Imprimir compareDistances();
FinAlgoritmo
```
Caso Falso: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210452676-e98d1f5f-37fb-4b0a-8832-c95b523d7840.png) <br>
Caso Verdadero: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210452782-10af8856-45ea-4293-82e5-b559570bb99b.png)
