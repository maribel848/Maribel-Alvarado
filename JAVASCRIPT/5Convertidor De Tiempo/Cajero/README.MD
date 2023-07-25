
## CAJERO


````PSC
Funcion balance <- cashier ()
	Definir balance Como Real;
	balance = 1000;
	Repetir
		Imprimir "Selecciona una opción:";
		Imprimir "a. Depositar.";
		Imprimir "b. Retirar.";
		Imprimir "c. Salir.";
		leer option
		Si option = 'a' Entonces
			balance = balance + deposit()
		FinSi
		Si option = 'b' Entonces
			balance = balance - withdraw()
		FinSi
	Mientras Que option = "a" | option = "b"
Fin Funcion

Funcion value <- deposit()
	Imprimir "¿Cuánto deseas depositar?:";
	leer value
FinFuncion

Funcion value <- withdraw()
	Imprimir "¿Cuánto deseas retirar?:";
	leer value
FinFuncion

Algoritmo EjeCashier
	Imprimir cashier()
FinAlgoritmo
````
