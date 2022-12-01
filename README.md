# bucles.py
Bucles: For, While, Break, Continue, Pass

#BUCLES
#
#FOR
#
#for donde vamos a imprimir 10 números
print("==============================")
print("Imprimiendo 10 numero con el ciclo for")
for x in range(10):
	print(x)
#
#----------------------------------------------
#Cuando imprimimos dentro de un rango de números, por ejemplo 5,10
print("===================================")
print("Imprimiendo dentro de un rango de números")
for num in range(5,10):
	print(num)
#
#----------------------------------------------
#Cuando imprimimos con cadena de texto
print("===========================")
print("Imprimiendo cadena de texto")
for texto in 'Hola':
	print(texto)
#
#----------------------------------------------
#Imprime los elementos que se encuentran en la lista
print("====================================")
print("Imprimiendo los elementos dentro de una lista")
lista = ['Hola', 1,651,True]
for cad in lista:
	print(cad)
#
#----------------------------------------------
#
#WHILE
#
#Imprime 10 numero con el ciclo while
print("CICLO WHILE")
num = 0
while num < 10:
	print(num)
	num+=1
#
#----------------------------------------------
#
#BREAK, CONTINUE, PASS
#
print("==============================")
print("METODOS: BREAK, CONTINUE, PASS")
print("==============================")
print("METODO BREAK")
#
"""Crearemos un programa que imprima los número del 0 al 10, pero cuando
encuentre un 8 que en ese momento detenga la ejecución del ciclo"""
#
for num in range(10):
	print(num)

	if(num==8):
		break
#
print("===============")
print("METODO CONTINUE")
print("===============")
#
"""Lo que realiza este metodo es que imprime valor * valor, multiplica
numero * numero hasta llegar al 9 ya que inicia desde el 1*1 y termina hasta
el 9*9, el unico valor que no esta es el 0*0, esto se debe a que en el caso
de detectar 0 le indicamos con el "continue" que simplemente no terminaŕa
el bucle y que continuará con el siguiente:"""
#
for num in range(10):
	if num == 0:
		continue

	valor = num * num
	print(valor)
#
print("===========")
print("METODO PASS")
print("===========")
#
"""
El metodo pass lo utilizamos cuando queramos crear una clase, método,
funcion, bucle o condicional, pero en el que todavía no queremos definir
ningún comportamiento.
"""
#
num = 10
while num < 10:
		pass

