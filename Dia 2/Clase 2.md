
<h1>Python</h1>
<h5>Es un lenguaje de programación fácil de leer que permite asignación de variables, operaciones matemáticas, condicionales y manipulaciones de cadenas, entre otros. </h5>
<h5>Tipos de Datos en python</h5>
1. Número (Number) - Python admite enteros y números de punto flotante de forma nativa:

```python
num= 42
num_flot = 3.14
```


1. Cadena de texto (String):

```python

string = "Hola, mundo!"
```

 
	1. Booleano (Boolean) - Los valores booleanos son `True` y `False` (con la primera letra en mayúscula):

```python

is_student = True
is_student = False
```

 
1. Valor nulo (None) - Similar al valor `null` en JavaScript:

```python

nul = None
```


1. Lista (List) - Una colección ordenada y modificable de elementos:

```python

list = [1, 2, 3, "cuatro", 5.0]
```


1. Tupla (Tuple) - Una colección ordenada e inmutable de elementos:

```python

tuple = (1, 2, 3, "cuatro", 5.0)
```


1. Conjunto (Set) - Una colección no ordenada y sin elementos duplicados:

```python

set = {1, 2, 3, "cuatro", 5.0}
```


1. Diccionario (Dictionary) - Una colección de pares clave-valor:

```python

dictionary = {
    "nombre": "Juan",
    "edad": 30,
    "ciudad": "México"
}
```

<h2>Funciones y Ayuda</h2>

Incluye la ayuda integrada, los argumentos por defecto, las funciones que no devuelven valores y las funciones de orden superior.

```python
def mutiply_by_two(x):

	return x * 2
	
help(multiply_by_two)
```

```python
def greet(person):
	return f"Hello, {person}!"
def repeat(fun, times,arg):
	for _ in range(times):
		print(func(arg))
repeat(greet, 3, 'OpenAI')
```

<h3>Booleans y Condicionales</h3>
Python usa bool con valores True/False, Se usan operadores booleanos, comparaciones y condicionales. Permite controlar la ejecución del código.
<h4>Ejemplos</h4>
```python
def is_even(num):
	return num % 2 == 0 
print("Is 2 even", is_even(2))
print("Is 2 even", is even (3))
```

```python
def is_not_zero(num):
	return not (num == 0)
print("Is 2 not zero?", is_not_zero(2))
print("Is 0 not zero?", is_not_zero(0))
```

<h3>Listas</h3>
Son secuencias ordenadas de valores que pueden ser modificadas e indexadas, también ofrecen funciones útiles para manipularlas.
<h5>Ejemplos</h5>
```python
fruits = ['apple', 'banana', 'cherry']
print(fruits[0])
print(fruits[-1])
```

<h3>Bucles y compresión la lista</h3>
Los bucles en python (for, while) repiten código determinado. Las compresiones de listas permiten condensar bucles y condicionales en una sola línea.

```python
city_population = {'New York': 8.4,
				   'Los Angeles': 3.9,
				   'Chicago': 2.7}
for city, population in city_population.items():
	print(f'The population of {city}'+
			f'is' {population} million.)
			
```

<h3>Strings y diccionarios</h3>
Las cadenas son flexibles e inmutables, soportando múltiples métodos de manipulación. Las listas y diccionarios también son útiles para organizar datos.

```python
planets = [
    'Mercury', 'Venus', 'Earth',
    'Mars', 'Jupiter', 'Saturn',
    'Uranus', 'Neptune'
]
planet_initials = {
    planet: planet[0]
    for planet in planets
}

print(planet_initials)
```
<h3>Trabajando con librerías externas</h3>
Python permite la importación de librerías, ya sea estándar o personalizadas, a través de importaciones. Las librerías contienen módulos que son colecciones de funciones y valores.

```python
import math 

number = float(input("Enter a number: ")) 

function from the "math" library square_root = math.sqrt(number) 

print("The square root of", number, "is:", square_root)
```

