```
Algoritmo ascDescNumbers
	Imprimir "--- Ascending and Descending Numbers ---";
	Imprimir "Ingrese un numero: ";
	Leer num;
	Imprimir "Operaciones Disponibles: ";
	Imprimir "1. Imprimir en Orden Ascendente.";
	Imprimir "2. Imprimir en Orden Descendente.";
	Imprimir "Ingrese la operacion a ejecutar: ";
	Leer operacion;
	Segun operacion Hacer
		"1":
			Para iterador<-0 Hasta num Hacer
				Imprimir ConvertirATexto(iterador);
			Fin Para
		"2":
			Para iterador<-num  Hasta 0 Hacer
				Imprimir ConvertirATexto(iterador);
			Fin Para
		De Otro Modo:
			Imprimir "¡¡Opcion No Disponible!!";
	Fin Segun	
FinAlgoritmo
```

Orden Ascendente: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209071535-cab24fd1-a83f-42b1-bab0-c57225fba894.png) <br>
Orden Descendente: <br>
![imagen](https://user-images.githubusercontent.com/116420679/209071631-134e8a6b-b22d-4ce3-b351-183f29b72f61.png)
