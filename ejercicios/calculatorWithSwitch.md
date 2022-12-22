```
Algoritmo calculatorWithSwitch
	Imprimir "---- Calculadora ----";
	Imprimir "Ingrese el primer numero: "; 
	Leer n1;
	Imprimir "Ingrese el segundo numero: "; 
	Leer n2;
	Imprimir "Ingrese una operacion: +,-,*,/";
	Leer operacion;	
	
	Si operacion=="+" O operacion=="-" O operacion=="*" O operacion=="/" Entonces
		Imprimir "Procesando: ",ConvertirATexto(n1),operacion,ConvertirATexto(n2);
		Segun operacion Hacer		
			"+":
				suma=n1+n2;
				Imprimir "Resultado: ",ConvertirATexto(suma);
			"-":
				resta=n1-n2;
				Imprimir "Resultado: ",ConvertirATexto(resta);
			"*":
				mul=n1*n2;
				Imprimir "Resultado: ",ConvertirATexto(mul);
			"/":
				div=n1/n2;
				Imprimir "Resultado: ",ConvertirATexto(div);
			De Otro Modo:
				Imprimir "¡¡Operacion No Valida!!";
		Fin Segun
	SiNo
		Imprimir "¡¡Operacion No Valida!!";
	Fin Si
FinAlgoritmo
```

Suma: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209060750-2cc15ca4-7c87-4f46-bf4f-191a100177e0.png) <br>
Resta: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209060868-04efa280-b1e7-4a94-ad97-315cdc9df44d.png) <br>
Multiplicacion: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209061103-137253ad-3eab-400c-bd70-7706017372fa.png) <br>
Division: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209061018-052281cc-d9ec-459f-9ae2-7b3fbdf6f829.png) <br>
ERROR: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209061242-95cefcaa-eccf-4589-b2bb-bab27e8e0483.png)

