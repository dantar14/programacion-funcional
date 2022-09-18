#presentacion
#problemas vistos en clase
##1.funcion que imprima mensaje del nombre de una persona y su edad

##1.1 se manda a llamar una funcion que reciba el nombre y edad del usuario

##1.2 codigo
https://github.com/dantar14/funciones/blob/main/trabajo%20suma.py

##1.3 Prueba de escritorio
##1.4 mensaje 
"Hola (nombre) tienes (edad) años"

##1.5 salida
Hola dante tienes 19 años

##2.1 impresion de alumnos en forma de tupla y set

##2.2 se crea una variable con el nombre alumnos y se imprime en forma de tupla y set agregando un len para la longitud del texto

##2.3 prueba de escritorio 
##2.4 mensaje
alumnos = ["Hugo","Paco","Luis","Lupita"]
print(f"Alumnos: {alumnos}")
for i in range(4): print(f"Alumos: {alumnos[i]}") tuplas alumnos = ["Hugo","Paco","Luis","Lupita"] print(f"Alumnos: {alumnos}")
for i in range(len(alumnos)): print(f"Alumos {i+1}: {alumnos[i]}") sets alumnos = ["Hugo","Paco","Luis","Lupita"] print(f"Alumnos: {alumnos}")

##2.5 salida
Nombres de los alumnos en forma de tupla

##3.1 impresion de binarios,unicodigos,hexadecimal y octal

##3.2 se hace un print f y en llaves se pone el numero a transformar seguido a lo que se quiera hacer,como covertir a binario,octal,hexadecimal u obtener
su codigo asci

##3.3 prueba de escritorio
##3.4 mensaje
print(f"{25:b}")
print(f"{65:c}")
print(f"{255:x}")
print(f"{255:o}")
##3.5 salida
imprime el 25 en binario,el codigo asci de 65,255 en hexadecimal y en octal

##4.1 impresion de calificaciones de varios alumnos
##4.2 se hacen las variables e,alumnos y las variables de las materias para almacenar datos y se manda a hacer una funcion llamada reporte en la
que se especifique con fmt que se imprimira en forma de reporte o que sea como un reporte
##4.3 prueba de escritorio
##4.4 mensaje
e =["nombre", "Est Dat", "Prog Func", "inglés"]
 alumnos = ["Hugo", "Paco", "Luis", "Lupita"]
 m_e_d=[9,7,9,8]
 m_p_f=[10,8,7,9]
 m_i=[6,9,7,8]
 def reporte(fmt:int):
     print(f"{e[0]:^{fmt}}{e[1]:^{fmt}}{e[2]:^{fmt}}{e[3]:^{fmt}}")
     for i in range(len(alumnos)):
      print(f"{alumnos[i]:*<{fmt}}{m_e_d[i]:+^{fmt}}{m_p_f[i]:#^{fmt}}{m_i[i]:-^{fmt}}")
if __name__== "__main__": 
    reporte(15)
##4.5 salida
se imprime las materias,los alumnos y las califaciones que han sacado en cada materia simulando un reporte por su estructura

##5.1 Escriba una funcion que genere una tabla de multiplicar recibiendo como argumento la cantidad de numeros 
y la lista a generar
##5.2 se mandan a llamar dos funciones la primera "tablas" sera la que incremente el multiplicador de los numeros mandados a llamar en el
main y que se cree otra variable llamada tabla que se usara para incrementar el numero a multiplicar
##5.3 prueba de escritorio
##5.4 mensaje 
def tablas(m:int, n:int, t:int, fmt:int):
    for i in range(1,m+1):
        tabla(m,i,fmt)

def tabla(n:int, t:int, fmt:int):
      for i in range(1,n+1):
       print(f"{t:^{fmt}}x{i:^{fmt}}={i*t:^{fmt}}")

if __name__ == "__main__":
      tabla(3,4,6)
      
##5.5 salida
imprimira en forma de tabla el numero 4 hasta que el multiplicador llegue a 3 y la longitud del texto sea de 6

##6.1 impresion de listas

##6.2 se imprimen dos listas una con valores enteros(numeros) y la otra imprimira varios caracteres que sea numeros enteros,flotantes,
una letra,un true y agrupaciones

##6.3 prueba de escritorio
##6.4 mensaje
lista1 = [ 1,2,3,4]
 print(lista1)
 lista2 = [1,3.14,"a",True, [4,5,6], (1,2,3), {8,"a",5.4}]
 print(lista2)
    
##6.5
las dos listas imprimen lo que tenian dentro si sin importar si en la lista 2 no habia valores de tipo entero

##7.1 impresion del numero 1 hasta el 10

##7.2 se crea la variable lista_numeros seguido se crea un for en el que se incremente de l al 11 solo llegara al 10 por eso el 11
y se le agrega el append para que se vayan agregando a dicha variable y se imprima

##7.3 prueba de escritorio
##7.4 mensaje
lista_numeros=[]
for i in range(1,11):
     lista_numeros.append(i)
print(lista_numeros)

#7.5 salida
impresion de forma ascendente del 1 al 10
      
      
