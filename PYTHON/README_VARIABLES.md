# Tipos de Variables en Python

En Python, una variable es un contenedor para almacenar datos. El tipo de datos se infiere automáticamente.

### Tipos principales:
1. **Enteros (`int`)**: Números sin decimales.
2. **Flotantes (`float`)**: Números con decimales.
3. **Cadenas (`str`)**: Texto.
4. **Booleanos (`bool`)**: Verdadero o falso.

### Ejemplos:
```python
# Enteros
edad = 25

# Flotantes
altura = 1.75

# Cadenas
nombre = "Juan"

# Booleanos
es_mayor_de_edad = True

# Imprimir valores y sus tipos
print(edad, type(edad))           # 25 <class 'int'>
print(altura, type(altura))       # 1.75 <class 'float'>
print(nombre, type(nombre))       # "Juan" <class 'str'>
print(es_mayor_de_edad, type(es_mayor_de_edad))  # True <class 'bool'>
