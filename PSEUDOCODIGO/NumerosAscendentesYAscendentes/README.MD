### numeros ascendentes y descendntes



```psc
Algoritmo numerosAscendentesYAscendentes
	escribir "===== numeros ascendentes y descendentes====="
	escribir " ingrese un numero"
	leer numero
	escribir " operaciones disponibles"
	imprimir "1. imprimir en orden ascendente"
	imprimir "2. imprimir en orden descendente"
	imprimir " ingrese operacion a ejecutar" 
	leer opcion
	segun opcion hacer
		1:
			Para iterador = 0 Hasta numero Con Paso 1 Hacer
				imprimir ConvertirATexto(iterador)
			Fin Para
			2:
			Para iterador = numero Hasta  0 Con Paso -1 Hacer
				imprimir ConvertirATexto(iterador)
				
		fin para
		De Otro Modo:
			imprimir "opcion incorrecta"
	
	
	FinSegun
	
	
FinAlgoritmo
```
