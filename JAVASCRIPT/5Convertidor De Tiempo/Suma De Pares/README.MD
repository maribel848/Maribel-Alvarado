
````PSC

funcion result <- sumaDePares()
	definir result, suma como real;
	suma = 0;
	repetir 
		escribir "escribe un numero de 1 a 100"
		leer num
		si num < 1 & num > 100 Entonces
			escribir "numero invalido"
		sino 
			si num % 2 = 0
				suma = suma + num;
			FinSi
			
		FinSi
	mientras que num >=1 & num <= 100
	result = suma;
	FinFuncion
	
	Algoritmo suma_de_pares
	escribir sumaDePares()
	
	
FinAlgoritmo
````
