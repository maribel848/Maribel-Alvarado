## Precio Total


````psc
Funcion value <- TotalPrice (price, iva)
		Definir value Como Real;
		SI price > 3000 Entonces
			value = ( price + (price/100*iva) ) / 100*90
			escribir "Precio tota incuyendo IVA "
		SiNo
			valor = ( price + (price/100*iva) )

		FinSi
	Fin Funcion
	
	Algoritmo example_Totalprice 
		Imprimir TotalPrice(5000,21) 
		
FinAlgoritmo

````
