### Numero especial 

Algoritmo numeroEspecial
	leer numero
	si numero == 100 Entonces
		imprimir "este es un numero especial:"
		
	FinSi
	si numero < 1000 Entonces
		imprimir "este numero es casi especial:"
		
	FinSi
	si numero % 10 == 0 entonces  
		
		imprimir "este numero es casi especial:"
	sino 
		escribir "solo un numero regular:"
		
		
	FinSi
FinAlgoritmo

 
 ### modificado
* Algoritmo numeroEspecial
	leer n
	si n == 100 Entonces
		imprimir "este es un numero especial"
	Sino
		//diferente de 100
		SI n < 1000 & n % 10  == 0 entonces 
			imprimir  "este es un numero casi especial:"
		SiNo
			imprimir "este numero es regular:"
			
		 finsi
	FinSi
	
FinAlgoritmo

 
