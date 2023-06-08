### Calculadora simple con switch 


``````psc
Algoritmo calculadoraSimple
		Escribir  '======= Calculadora Simple ======='
		Escribir  'Ingrese primer numero'
		Leer n1
		Escribir  'Ingrese segundo numero"
		Leer n2
		Escribir  'Ingrese una operación: +,-,*,/'
		Leer op
		Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
			Escribir  'procesando :' +  ConvertirATexto(n1) + " " + op ConvertirATexto(n2)
			Segun op Hacer
				    '+':
				    Imprimir 'Resultado: ' + ConvertirATexto(n1 + n2)
					'-':
						Imprimir 'Resultado: ' + ConvertirATexto(n1 - n2)
					'*':
						Imprimir 'Resultado: ' + ConvertirATexto(n1 * n2)
					'/':
						Imprimir 'Resultado: ' + ConvertirATexto(n1 / n2)
				Fin Segun
			SiNo
				Imprimir 'La operación no es valida'
			FinSi
FinAlgoritmo

``````


