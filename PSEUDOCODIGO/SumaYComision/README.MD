## VENTAS Y COMISION


```` psc
Algoritmo ventasYComisiones
	
	definir ventaTotal Como Entero
	escribir "escriba el numero total de ventas a ingresar"
	leer cantidaddeventas
	suma= 0  
	para ventaTotal=1 Hasta cantidaddeventas con paso 1 Hacer
		escribir "escriba el valor de numero de la ventas" 
		leer cantidad
		suma = suma + cantidad
		 
	FinPara
	Imprimir "la Suma de la venta es de:" suma; 
	
	porcentaje= 0
	
	si cantidaddeventas <= 4 Entonces 
			escribir " la comision es :" suma * 0.10
			
		sino 
			escribir "el porcentaje de ventas es: ",  suma * 0.15
			
			
		FinSi
FinAlgoritmo
````
