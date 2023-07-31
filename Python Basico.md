		Es un lenguaje de programación fácil de leer que permite asignaciones de variables, operaciones matemáticas.

- Realizamos nuestro primer código en Python
![[Pasted image 20230725084843.png]]
Ejerciso 2

![[Pasted image 20230725091300.png]]
<h3>Listas</h3>
-  son secuencias ordenadas de valores que pueden ser modificadas e indexadas, también ofrecen funciones útiles para manipularlas 
![[Pasted image 20230726211118.png]]
***
<h3>Ejerciso en clases signos zodiacales</h3>
![[Pasted image 20230725100221.png]]
***
<h3>Bucles y comprensión de listas </h3>
Los Bucles en Python (for, while) repiten codigo determinado. Las compresiones de listas permiten condensar bucles y condicionales en una sola Línea.

![[Pasted image 20230725104830.png]]
***
<h3>String y diccionarios</h3>
Las cadenas son flexibles e inmutables, soportando múltiples métodos de manipulación. Las Listas y diccionarios también son útiles para organizar datos.
![[Pasted image 20230725110146.png]]
****
<h3>Trabajando con librerías externas</h3>
  Python permite la importación de librerías, ya sea estándar o personalizadas a través de importaciones. Las librerías contiene módulos que son colecciones de funciones y valores. 
                             - Pandas 
                             - Random
***
<h1>EJERCISIO EN CLASE SORTEO</h1>
import random

```Python

  

animals  = ['Perro', 'Gato', 'Delfin', 'Tiburon', 'Jirafa']

  

numbers = [1, 2, 3, 4]

  
  

def lottery():

  
  

                lottery = input("Ingresar su numero de loteria: ")

  

lottery()

  

tamano_lista = 4

  

rango_minimo = 1

  

rango_maximo = 4

  
  

lista_aleatoria = [random.randint(rango_minimo, rango_maximo)

                   for _ in range(tamano_lista)]

  
  

if lottery == lista_aleatoria:

  

                 print("Ganaste la loteria")

  

else:

  

         print("Lo sentimos esta es la lista de numeros de loteria que ganaron: ", lista_aleatoria)

  
  

def animal():

  
  

                animal = input("Ingrese su Animal: ")

  

animal()

  
  

lista_animal =

  
  

if animal == lista_animal:

  

                     print("Ganaste otro boleto")

  

else:


                print("Lo sentimos el animal ganador es: ", random.choice(animals))