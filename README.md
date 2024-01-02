# Diccionario Básico en Python

Este es un proyecto simple que implementa un diccionario en Python.

## Descripción

El diccionario permite almacenar palabras y sus definiciones asociadas.

## Instalación

1. Clona este repositorio: `git clone https://github.com/tu-usuario/tu-proyecto.git`
2. Accede al directorio del proyecto: `cd tu-proyecto`

## Uso

1. Ejecuta el script principal: `python main.py`
2. Sigue las instrucciones en la consola para agregar, buscar o eliminar palabras.

## Ejemplo de Uso

```python
# Importa la clase Diccionario desde main.py
from main import Diccionario

# Crea una instancia del diccionario
mi_diccionario = Diccionario()

# Agrega una palabra y su definición
mi_diccionario.agregar_palabra("Python", "Un lenguaje de programación poderoso y fácil de aprender.")

# Busca una palabra
definicion = mi_diccionario.buscar_palabra("Python")
print(definicion)
