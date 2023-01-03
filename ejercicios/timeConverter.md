```
Funcion resultado <- TimeConverter(numberOfSeconds)
	Si numberOfSeconds<=0 Entonces
		Imprimir "Ingrese un numero positivo";
	SiNo
		seconds=numberOfSeconds % 60;
		minutes=Trunc(numberOfSeconds/60) % 60;
		hours=Trunc(numberOfSeconds/3600) % 24;
		days=Trunc(numberOfSeconds/86400);
		resultado=Concatenar("Days: ",ConvertirATexto(days));
		resultado=Concatenar(resultado,", Hours: ");
		resultado=Concatenar(resultado,ConvertirATexto(hours));
		resultado=Concatenar(resultado,", Minutes: ");
		resultado=Concatenar(resultado,ConvertirATexto(minutes));
		resultado=Concatenar(resultado,", and Seconds: ");
		resultado=Concatenar(resultado,ConvertirATexto(seconds));
	Fin Si
FinFuncion

Algoritmo algoritmoTimeConverter
	Imprimir TimeConverter(4000);
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210450627-3389613c-170f-49db-bdb6-e94c86f9fbf4.png)
