# Diccionarios en Python

Los diccionarios son colecciones desordenadas de pares clave-valor.

## Crear un diccionario:
```python
persona = {"nombre": "Carlos", "edad": 30, "ciudad": "Madrid"}
print(persona)
````
## Acceder a valores:
```python
print(persona["nombre"])  # Carlos
````
## Modificar valores:
```python
persona["edad"] = 31
print(persona)  # {'nombre': 'Carlos', 'edad': 31, 'ciudad': 'Madrid'}
````
## Añadir nuevas claves:
```python
persona["profesión"] = "Ingeniero"
print(persona)  # {'nombre': 'Carlos', 'edad': 31, 'ciudad': 'Madrid', 'profesión': 'Ingeniero'}
````
## Iterar sobre un diccionario:
```python
for clave, valor in persona.items():
    print(f"{clave}: {valor}")
````
