# Bucles en Python

Los bucles son estructuras que permiten repetir un bloque de código.

## 1. Bucle `for`
Se utiliza para iterar sobre elementos de una secuencia (lista, rango, cadena, etc.).

```python
# Iterar sobre una lista
numeros = [1, 2, 3, 4, 5]
for numero in numeros:
    print(numero)

# Usar `range`
for i in range(5):
    print(f"Iteración: {i}")
````
## 2. Bucle `while`

Repite el bloque mientras la condición sea True.

```python
contador = 0
while contador < 5:
    print(f"Contador: {contador}")
    contador += 1
````
## Salir de un bucle: break y continue

```python
for i in range(10):
    if i == 5:
        break  # Termina el bucle
    if i % 2 == 0:
        continue  # Salta a la siguiente iteración
    print(i)
````


