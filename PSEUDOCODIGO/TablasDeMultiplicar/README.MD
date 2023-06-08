### Tablas de multiplicar



Algoritmo tablasDeMultiplicar 
	numeroUsuario = 0
	escribir "ingrese un numero" 
	leer numeroUsuario
	escribir "tablas del 1 al 10 del numero" ,numeroUsuario  , numeroUsuario
	contadorTabla = 1
	mientras contadorTabla <= 10 Hacer
		imprimir numeroUsuario, " * " , contadorTabla , "=" numeroUsuario * contadorTabla
		contadorTabla = contadorTabla + 1
	FinMientras
	
FinAlgoritmo 
