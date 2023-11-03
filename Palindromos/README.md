# Ejercicio: Detección de Palíndromos

## 1. Objetivos:
- Entender y utilizar las listas en Python para manipular cadenas de caracteres.
- Aprender a utilizar la anotación de tipos (`typing`) para mejorar la legibilidad y el chequeo estático del código.
- Desarrollar una función que verifica si una cadena de texto es un palíndromo.

## 2. Problema:
Se desea implementar una función que determine si una palabra o frase es un palíndromo. Un palíndromo es una secuencia de caracteres que se lee igual de adelante hacia atrás que de atrás hacia adelante, ignorando espacios, signos de puntuación y diferencias entre mayúsculas y minúsculas.

## 3. Alcanzables:
Al resolver el problema, se debe obtener una función que:

- Reciba una cadena de texto como argumento.
- Retorne `True` si la cadena es un palíndromo.
- Retorne `False` si la cadena no es un palíndromo.
- Incluya anotaciones de tipo para sus argumentos y su valor de retorno.

## 4. Qué se necesita:
Para preparar el entorno virtual y la instalación de paquetes, sigue estos pasos:

1. Crear un entorno virtual (se asume que ya tienes Python instalado):
   ```sh
   python -m venv venv
   ```
2. Activar el entorno virtual:
   - En Windows:
     ```sh
     .\venv\Scripts\activate
     ```
   - En macOS y Linux:
     ```sh
     source venv/bin/activate
     ```
3. Instalar los paquetes necesarios utilizando pip:
   ```sh
   pip install pandas autopep8
   ```

## 5. Referencias:
Consulta la documentación oficial de Python para entender mejor las listas, el manejo de cadenas y la anotación de tipos:

- Documentación sobre listas en Python: [Python Lists](https://docs.python.org/3/tutorial/introduction.html#lists)
- Documentación sobre el manejo de cadenas de texto: [Python Strings](https://docs.python.org/3/tutorial/introduction.html#strings)
- PEP 484 sobre la anotación de tipos: [Type Hints](https://www.python.org/dev/peps/pep-0484/)

Recuerda tratar de eliminar espacios y signos de puntuación de la cadena y convertirla a minúsculas antes de verificar si es un palíndromo. Esto permitirá que la función sea más flexible y pueda evaluar correctamente frases completas además de palabras únicas.

