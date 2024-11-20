
# Listas en Python

Las listas (arrays) son estructuras de datos que almacenan una colección de elementos ordenados.

## Crear una lista:
```python
frutas = ["manzana", "banana", "cereza"]
print(frutas)  # ['manzana', 'banana', 'cereza']
````
Acceder a elementos:
```python
print(frutas[0])  # manzana
print(frutas[-1]) # cereza
````
## Operaciones comunes:
```python
# Añadir elementos
frutas.append("naranja")
print(frutas)  # ['manzana', 'banana', 'cereza', 'naranja']

# Eliminar elementos
frutas.remove("banana")
print(frutas)  # ['manzana', 'cereza', 'naranja']

# Longitud de la lista
print(len(frutas))  # 3
````
## Iterar sobre una lista:
```python
for fruta in frutas:
    print(fruta)
````
