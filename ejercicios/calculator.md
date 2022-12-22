```
Algoritmo simpleCalculator
	Imprimir "---- Calculadora ----";
	Imprimir "Ingrese el primer numero: "; 
	Leer n1;
	Imprimir "Ingrese el segundo numero: "; 
	Leer n2;
	Imprimir "Ingrese una operacion: +,-,*,/";
	Leer operacion;	
	
	Si operacion=="+" O operacion=="-" O operacion=="*" O operacion=="/" Entonces	
		Imprimir "Procesando: ",ConvertirATexto(n1),operacion,ConvertirATexto(n2);
		Si operacion=="+" Entonces
			suma=n1+n2;
			Imprimir "Resultado: ",ConvertirATexto(suma);
		FinSi
		Si operacion=="-" Entonces
			resta=n1-n2;
			Imprimir "Resultado: ",ConvertirATexto(resta);
		FinSi
		Si operacion=="*" Entonces
			mul=n1*n2;
			Imprimir "Resultado: ",ConvertirATexto(mul);
		FinSi
		Si operacion=="/" Entonces
			div=n1/n2;
			Imprimir "Resultado: ",ConvertirATexto(div);
		FinSi
	SiNo
		Imprimir "¡¡Operacion No Valida!!";
	Fin Si
FinAlgoritmo
```
Suma: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209032022-53d0e00c-7889-4923-b6d3-39639b163fa7.png) <br>
Resta: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209032079-b30db83a-482b-4157-8966-61cd24d15028.png) <br>
Multiplicacion: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209032144-c83c5147-fa5c-4ec9-b219-1eae05c07fbe.png) <br>
Division: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209032186-4982d603-e91f-45ed-92de-3d1092cc0950.png) <br>
ERROR: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209032233-b774c59e-abed-40f5-b591-cff117d25981.png)
