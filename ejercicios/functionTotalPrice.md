```
Funcion priceIncludingVAT <- TotalPrice(price,vat)
	Si price>3000 Entonces
		priceIncludingVAT=(price + (price/100*vat)) / 100*90;
	SiNo
		priceIncludingVAT=(price + (price/100*vat));
	Fin Si
FinFuncion

Algoritmo functionTotalPrice
	Imprimir TotalPrice(5000,21);
FinAlgoritmo
```
![imagen](https://user-images.githubusercontent.com/116420679/210444283-fce3e5ae-cec7-400c-948e-d2dac0355e30.png)

