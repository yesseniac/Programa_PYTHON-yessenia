Programa_PYTHON-yessenia

##Imprimir los numeros del 1 al 50 y calcular la suma de todos los numeros 
###pares e impares.
n = 1
p = 0
i = 0
while n <= 50:
    print n,
    if n%2 == 0:
        p += n
    else:
        i += n
    n += 1
print '\nLa suma de los pares es igual a %i' % p
print 'La suma de los impares es igual a %i' % i
 
