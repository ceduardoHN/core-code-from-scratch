```
Algoritmo greetings
	Imprimir "--- Cheers ---";
	numSaludos=0;
	
	Repetir
		Imprimir "Ingrese la hora actual (0-23): ";
		Leer hora;
		Si  hora>=0 Y hora<=23 Entonces			
			Si hora>=0 Y hora<=12 Entonces
				Imprimir "Buenos dias!";
			FinSi
			Si hora>=13 Y hora<=18 Entonces
				Imprimir "Buenas tardes!";
			FinSi
			Si hora>=19 Y hora<=23 Entonces
				Imprimir "Buenas noches!";
			FinSi
			numSaludos=numSaludos+1;
		SiNo
			Imprimir "¡¡Hora No Valida!!";
		FinSi
		
		Imprimir "Deseas continuar? Si/No";
		Leer decision;
	Hasta Que decision=="no" O decision=="No" O decision=="NO"
	
	Imprimir "";
	Imprimir "Cantidad de Saludos Realizados: ",ConvertirATexto(numSaludos);
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/209076360-8512681f-8bc8-4d5d-9a20-3977f654bda6.png)

