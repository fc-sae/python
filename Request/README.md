## Ejercicio: Explorador de Personajes de Rick and Morty

### 1. Objetivos:
- Familiarizarse con el uso de entornos virtuales en Python.
- Aprender a realizar solicitudes HTTP GET utilizando el módulo `requests`.
- Manipular y procesar la respuesta JSON de una API.
- Implementar una interfaz de línea de comandos simple para interactuar con la API de Rick and Morty.

### 2. Problema:
Quieres crear un script que consulte la API de Rick and Morty para obtener información sobre personajes basados en la entrada del usuario. El usuario podrá ingresar el nombre de un personaje, y tu script deberá encontrar y mostrar la información correspondiente, como la especie, el estado (vivo, muerto, desconocido) y en qué episodios ha aparecido.

### 3. Alcanzables:
Tu script debe ser capaz de:

- Pedir al usuario que introduzca el nombre de un personaje.
- Realizar una solicitud HTTP a la API de Rick and Morty para buscar información sobre ese personaje.
- Procesar la respuesta JSON y extraer la información relevante del personaje.
- Imprimir los detalles del personaje de manera legible para el usuario.

### 4. Qué se necesita:
Para preparar tu entorno y ejecutar este ejercicio, sigue estos pasos:

1. Asegúrate de tener Python instalado y funcionando en tu sistema.
2. Crea un entorno virtual en tu directorio de trabajo:
   ```sh
   python -m venv env_rickmorty
   ```
3. Activa el entorno virtual:
   - En Windows:
     ```sh
     .\env_rickmorty\Scripts\activate
     ```
   - En macOS y Linux:
     ```sh
     source env_rickmorty/bin/activate
     ```
4. Con el entorno activo, instala el módulo `requests` si aún no lo has hecho:
   ```sh
   pip install requests
   ```

### 5. Referencias:
Aquí están las referencias que te ayudarán a realizar este ejercicio:

- Documentación del módulo `requests` para hacer solicitudes HTTP: [Requests Documentation](https://docs.python-requests.org/en/latest/)
- Documentación de la API de Rick and Morty: [API Documentation](https://rickandmortyapi.com/documentation)


Al realizar la solicitud a la API de Rick and Morty, recuerda manejar adecuadamente los errores y excepciones que podrían ocurrir, como solicitudes con errores de red o un nombre de personaje que no existe en la base de datos. Además, dado que un nombre puede corresponder a múltiples personajes, tu script deberá ser capaz de manejar múltiples resultados y presentarlos al usuario de forma clara.