## Direcion Inversa y Tamaño


````psc

Funcion result <- ReverseDirectionAndSize (string)
		Definir result Como Caracter;
		result = "";
		Para count = Longitud(string) Hasta 0 Con Paso -1 Hacer
			palabra = Subcadena(string,count,count);
			SI palabra = Mayusculas(palabra) Entonces
				palabra = Minusculas(palabra)
			FinSi
			result = Concatenar(result, palabra)
		FinPara
	Fin Funcion
	
	Algoritmo EjeReverseDirectionAndSize 
		Imprimir ReverseDirectionAndSize("lindo")

FinAlgoritmo
````
