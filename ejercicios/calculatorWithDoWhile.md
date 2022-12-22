```
Algoritmo calculatorWithDoWhile
	Imprimir "---- Calculadora ----";
	Repetir
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
		
		Imprimir "";
		Imprimir "Deseas continuar con otra operacion? Si/No";
		Leer decision;
	Hasta Que decision=="no" O decision=="No" O decision=="NO"
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/209069099-2affe1e5-a751-4b6f-8eac-eb09eccc11f6.png)
