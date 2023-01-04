```
Funcion resultado <- cashier()
	balance=1000;
	Repetir
		Imprimir "Select an option: ";
		Imprimir "a. To Deposit.";
		Imprimir "b. Withdraw.";
		Imprimir "c. Go Out.";
		Leer option;
		Si option=="a" Entonces
			balance=balance+deposit();
		SiNo
			Si option=="b" Entonces				
				balance=balance-withdraw();
			FinSi
		Fin Si
	Hasta Que option=="c";
	resultado=balance;
FinFuncion
Funcion deposito <- deposit()
	Imprimir "How much do you want to deposit?";
	Leer deposito;
FinFuncion
Funcion retiro <- withdraw()
	Imprimir "How much do you want to withdraw?";
	Leer retiro;
FinFuncion

Algoritmo algoritmoCashier
	Imprimir cashier();
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210671386-1eacae7a-b845-4be2-a2bf-c4cff62fc5af.png)
