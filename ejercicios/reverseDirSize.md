```
Funcion resultado <- ReverseDirectionAndSize(cadenaTexto)
	Para i <- Longitud(cadenaTexto) Hasta 0 Con Paso -1 Hacer
		letra = Subcadena(cadenaTexto,i,i);
		SI letra = Mayusculas(letra) Entonces
			letra = Minusculas(letra);
		SiNo
			letra = Mayusculas(letra);
		FinSi
		resultado = Concatenar(resultado,letra);
	FinPara
FinFuncion

Algoritmo reverseDirSize
	Imprimir ReverseDirectionAndSize("TexTo");
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210446084-f170b12e-9845-4b76-96b3-d2b6b199736b.png)
