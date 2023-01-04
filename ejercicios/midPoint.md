```
Funcion resultado <- midPoint(value1,value2)
	Si value1<value2 O value2<value1 Entonces
		Si value1<value2 Entonces
			resta=value2-value1;
			division=resta/2;
			resultado=Concatenar("The MidPoint is: ",ConvertirATexto(value1+division));
		FinSi
		Si value2<value1 Entonces
			resta=value1-value2;
			division=resta/2;
			resultado=Concatenar("The MidPoint is: ",ConvertirATexto(value2+division));
		FinSi
	SiNo
		resultado=Concatenar("The MidPoint is: ",ConvertirATexto(value1));
	Fin Si
FinFuncion

Algoritmo algoritmoMidPoint
	Imprimir midPoint(40,80);
	Imprimir midPoint(90,-70);
	Imprimir midPoint(8,8);
	Imprimir midPoint(-8,-8);
	Imprimir midPoint(-10,130);
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210647914-caaa2f73-74a4-4372-a792-97db83ba1d05.png)
