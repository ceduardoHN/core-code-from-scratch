```
Algoritmo tossCoin
	Imprimir "Enter the Name of the First Player: ";
	Leer namePlayer1;
	Imprimir "Enter the Amount to play: ";
	Leer amountPlayer1;
	Imprimir "Enter the Name of the Second Player: ";
	Leer namePlayer2;
	Imprimir "Enter the Amount to play: ";
	Leer amountPlayer2;
	
	bandera=Verdadero;
	winAmount=Aleatorio(1,2);
	
	Si amountPlayer1<=0 Y amountPlayer2<=0 Entonces
		Imprimir "Game Canceled";
		bandera=Falso;
	SiNo
		Si amountPlayer1<=0 Entonces
			Imprimir "Player wins: ",Mayusculas(namePlayer2)," amount won: 0";
			bandera=Falso;
		FinSi
		Si amountPlayer2<=0 Entonces
			Imprimir "Player wins: ",Mayusculas(namePlayer1)," amount won: 0";
			bandera=Falso;
		FinSi
	FinSi
	
	Si winAmount==1 Y bandera=Verdadero Entonces
		Imprimir "Player wins: ",Mayusculas(namePlayer1)," amount won: ",amountPlayer2;
	FinSi
	Si winAmount==2 Y bandera=Verdadero Entonces
		Imprimir "Player wins: ",Mayusculas(namePlayer2)," amount won: ",amountPlayer1;
	Fin Si
FinAlgoritmo
```
Casos Correctos: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210284501-ebf38683-aa01-436c-8b79-ff68efc5abd9.png)
![imagen](https://user-images.githubusercontent.com/116420679/210284531-5678ae5f-858a-4fb1-9506-5b125f79000f.png) <br>
Casos Incorrectos: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210284652-4d894b36-4085-4af0-84ec-5a4dc68cfd27.png)
![imagen](https://user-images.githubusercontent.com/116420679/210284669-07083a54-0e23-4c29-b165-b9e4b8aa3eb4.png) <br>
Juego Cancelado: <br>
![imagen](https://user-images.githubusercontent.com/116420679/210284730-efb5d465-ac87-4790-be8e-ce41505d2e0e.png)
