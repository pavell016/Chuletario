### **README_Funciones.md**

# Funciones en Python

Las funciones son bloques de código reutilizables que se pueden llamar con un nombre.

## Definir una función:
```python
def saludar(nombre):
    print(f"Hola, {nombre}!")

# Llamar a la función
saludar("María")  # Hola, María!
````

## Funciones con retorno:
```python
def sumar(a, b):
    return a + b

resultado = sumar(5, 3)
print(resultado)  # 8
````

## Parámetros opcionales:

```python
def presentar(nombre, edad=18):
    print(f"Nombre: {nombre}, Edad: {edad}")

presentar("Luis")           # Nombre: Luis, Edad: 18
presentar("Ana", edad=25)   # Nombre: Ana, Edad: 25
````

## Funciones Lambda:

Son funciones anónimas y cortas.
```python
doblar = lambda x: x * 2
print(doblar(4))  # 8
````
