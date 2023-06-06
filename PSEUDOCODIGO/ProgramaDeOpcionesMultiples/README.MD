### Programa de opciones multiples



Algoritmo opcionMultiple
	escribir  "=====opcion multiple====="
	escribir "opciones disponibles"
	escribir" 1. suma de dos numeros"
	escribir " 2. dia de la semana"
	escribir "3. calcular longitud de texto"
	escribir"ingrese opcion" 
	leer opcion
	segun opcion hacer 
		"1":
			escribir "suma de dos numeros"
			escribir "ingrese el primer numero"
			leer primerNumero
			escribir "ingrese el segundo numero"
			leer segundoNumero
			imprimir "resultado: " + ConvertirATexto(primerNumero + segundoNumero)
			
		"2":
			escribir"dia de la semana"
			escribir "ingrese el dia de la semana (1-7)"
			leer dia
			segun dia Hacer
				"1":
					imprimir "lunes"
				"2":	
					imprimir "martes"
					"3":
						imprimir "miercoles"
					"4":
						imprimir "jueves"
					"5":
						imprimir "viernes"
					"6":
						imprimir "sabado"
					"7":
						imprimir "domingo"
						de otro modo:
							imprimir "el dia ingresado es incorrecto"
				FinSegun
		"3":
			escribir "longitud de una cadena" 
			escribir "ingrese un texto"
			leer  texto
			 escribir "longitud de texto:  " + ConvertirATexto(longitud(texto))
			
			
		De Otro Modo:
		imprimir	"la opcion es incorrecta"

	
	fin segun
	
FinAlgoritmo

