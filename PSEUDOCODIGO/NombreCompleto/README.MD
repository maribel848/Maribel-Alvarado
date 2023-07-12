## NOMBRE COMPLETO

````psc

Algoritmo fullName
		Escribir "Escribe un nombre"
		leer first_name
		Escribir "Escribe un apellido"
		leer last_name
		corrected_first_name = Mayusculas(Subcadena(first_name,0,1)) + Minusculas(Subcadena(first_name,2,Longitud(first_name)-1))
		corrected_last_name = Mayusculas(Subcadena(last_name,0,1)) + Minusculas(Subcadena(last_name,2,Longitud(last_name)-1))
		Imprimir corrected_first_name, "  ",corrected_last_name

	
FinAlgoritmo
````
