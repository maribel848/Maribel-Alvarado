 ### tablas de multiplicar con bucle for
 
 
 
 ```psc
Algoritmo tablasDeMultiplicarConBucleFor
		Imprimir '======= Tablas de Multiplicación ======='
		Imprimir 'Ingrese la tabla a calcular:'
		Leer tabla
		Imprimir '  Tabla de ' + ConvertirATexto(tabla) + ' tablas de '
		

			Para iterador<-1 Hasta 10  Con Paso 1 Hacer
				Imprimir ConvertirATexto(tabla) ' *  ' + ConvertirATexto(iterador) + ' = ' ConvertirATexto(tabla * iterador)
				
			Fin Para 
		
		
		

FinAlgoritmo

````

  
