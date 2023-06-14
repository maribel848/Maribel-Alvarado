```PSC


Algoritmo saludos
	imprimir "===== saludos====="
	definir continuar Como Caracter
	continuar <- "si"
	mientras continuar = "si" Hacer
		imprimir "ingrese la hora actual(0-23):"
	leer hora  
	si hora <= 12 Entonces
		
		imprimir " buenos dias"
	sino 
		si hora <=18 Entonces
			
			imprimir "buenas tardes"
		SiNo
			imprimir " buenas noches"
		FinSi
	FinSi
	
	imprimir "desea continuar? si/no"
	leer continuar
		
fin mientras
	
	
FinAlgoritmo
```
