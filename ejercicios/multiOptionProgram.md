```
Algoritmo multiOptionProgram
	Imprimir "---- Multi Opcion ----";
	Imprimir "Opciones Disponibles: ";
	Imprimir "1. Suma de Dos Numeros.";
	Imprimir "2. Imprimir Dia de la Semana.";
	Imprimir "3. Calcular Longitud de Texto.";
	Imprimir "Ingrese la opcion seleccionada: ";
	Leer operacion;
	
	Si operacion=="1" O operacion=="2" O operacion=="3" Entonces
		Segun operacion Hacer
			"1":
				Imprimir "-- Opcion 1. Suma de dos Numeros. --";
				Imprimir "Ingrese el primer numero: "; 
				Leer n1;
				Imprimir "Ingrese el segundo numero: "; 
				Leer n2;
				Imprimir "Procesando: ",ConvertirATexto(n1),"+",ConvertirATexto(n2);
				suma=n1+n2;
				Imprimir "Resultado: ",ConvertirATexto(suma);
			"2":
				Imprimir "-- Opcion 2. Imprimir Dia de la Semana. --";
				Imprimir "Escriba el dia de la semana en numeros (1-7): ";
				Leer numDia;
				Si numDia=="1" O numDia=="2" O numDia=="3" O numDia=="4" O numDia=="5" O numDia=="6" O numDia=="7" Entonces
					Segun numDia Hacer
						"1":
							Imprimir "Lunes";
						"2":
							Imprimir "Martes";
						"3":
							Imprimir "Miercoles";
						"4":
							Imprimir "Jueves";
						"5":
							Imprimir "Viernes";
						"6":
							Imprimir "Sabado";
						"7":	
							Imprimir "Domingo";
						De Otro Modo:
							Imprimir "¡¡Opcion No Disponible!!"
					Fin Segun
				SiNo
					Imprimir "¡¡Opcion No Disponible!!";
				Fin Si
			"3":
				Imprimir "-- Opcion 3. Calcular Longitud de Texto. --";
				Imprimir "Ingrese una cadena de texto: ";
				Leer cadenaTexto;
				Imprimir "La longitud de la cadena de texto es: ",Longitud(cadenaTexto);
			De Otro Modo:
				Imprimir "¡¡Opcion No Disponible!!";
		Fin Segun
	SiNo
		Imprimir "¡¡Opcion No Disponible!!";
	Fin Si
	
FinAlgoritmo
```

Opcion 1: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209064487-f63f57ad-1cdd-44ba-bcc7-7ea305f61376.png) <br>
Opcion 2: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209065078-6fd9a374-43e7-4074-bdb6-54f231b9c017.png) <br>
Error (de Opcion 2): <br>
![imagen](https://user-images.githubusercontent.com/116420679/209065125-0e5bf434-95fa-4663-b38f-84d10c78f811.png) <br>
Opcion 3: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209064639-01bd64f0-656a-4f5b-81d0-ecc2cbb7ab7a.png) <br>
ERROR: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209064808-ef634cf1-7098-4000-ae02-36834312938f.png)


