## Lanzar Monedas


````psc
Algoritmo lanzarmonedas
	Escribir " ingresa el nombre del primer jugador"
	leer  player1
	escribir " ingrese la cantidad a jugar"
	leer amount1
	escribir "ingresa el nombre del segundo jugador"
	leer player2
	escribir "ingrese la cantidad a jugar"
	leer amount2
	
	si amount1<=0 | amount2<=0 Entonces
		si amount1<=0 Y amount2<=0 Entonces
			escribir " juego cancelado"
			
		sino 
			si amount1<=0 Entonces
				escribir "jugador que gana:  ", Mayusculas(player2), "cantidad ganada: 0"
			sino 
				escribir "jugador que gana: ", Mayusculas(player1), "cantidad ganada: 0"
			FinSi
			
		FinSi
	sino 
		si Aleatorio(1,2) = 1 Entonces
			escribir "jugador que gana: " ,Mayusculas(player1), " cantidad ganada: ",amount1
		SiNo
			escribir " jugador que gana: " Mayusculas(player2), " cantidad ganada: " amount2
		
		FinSi
	FinSi
	
	
	
FinAlgoritmo
````
