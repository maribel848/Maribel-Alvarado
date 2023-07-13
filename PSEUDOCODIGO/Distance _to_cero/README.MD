

````psc
Algoritmo distance_to_zero
	escribir "escribe un numero"
	leer maxDistance
	Para count<-1 Hasta 4 Con Paso 1 Hacer
		escribir "escribe un numero"
		leer num
		si abs(num) > abs(maxDistance)Entonces
			maximadistance = num
		FinSi
	Fin Para
	escribir trunc(maximadistance)
	
FinAlgoritmo
````
