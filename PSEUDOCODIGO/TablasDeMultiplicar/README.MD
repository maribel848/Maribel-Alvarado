### Tablas de multiplicar



```psc
Algoritmo tablasDeMultiplicar 
	numeroUsuario = 0
	escribir "ingrese tabla a calcular" 
	leer numeroUsuario
	escribir "tablas del 1 al 10 del numero" ,numeroUsuario  
	contadorTabla = 1
	mientras contadorTabla <= 10 Hacer
		imprimir numeroUsuario, " * " , contadorTabla , " = " numeroUsuario * contadorTabla
		contadorTabla = contadorTabla + 1
	FinMientras
	
FinAlgoritmo  
```


```psc

                Algoritmo tablasDeMu
		Imprimir '======= Tablas de Multiplicación ======='
		Imprimir 'Ingrese la tabla a calcular:'
		Leer tabla
		Imprimir '  Tabla de ' + ConvertirATexto(tabla) + ' tablas de '
		iterador <- 1
		Mientras iterador <= 10 Hacer
			Imprimir ConvertirATexto(tabla) ' *  ' + ConvertirATexto(iterador) + ' = ' ConvertirATexto(tabla * iterador)
			iterador <- iterador + 1
		Fin Mientras


	
FinAlgoritmo

````
