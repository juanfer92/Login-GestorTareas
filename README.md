# Desarrollo de Aplicaciones en Flutter

## Objetivo
Este repositorio contiene dos actividades diseñadas para que los estudiantes practiquen el desarrollo de aplicaciones móviles utilizando Flutter.

## Actividad 1: Pantalla de Inicio de Sesión

### Objetivo
El objetivo de esta actividad es que los estudiantes desarrollen una pantalla de inicio de sesión funcional utilizando un framework de desarrollo móvil como Flutter.

### Descripción de la Actividad
Los estudiantes deberán crear una aplicación que incluya un formulario de login con los siguientes requisitos:

- Un campo de entrada para el correo electrónico.
- Un campo de entrada para la contraseña.
- Un botón para iniciar sesión.
- Validaciones para los campos de entrada.
- Un mensaje que indique si el inicio de sesión fue exitoso o fallido.

#### Funcionalidades opcionales:
- Persistencia de sesión.
- Un botón de "¿Olvidaste tu contraseña?".
- Integración con Firebase Authentication o una API.

---

## Actividad 2: Aplicación de Gestión de Tareas

### Objetivo
Desarrollar una aplicación que permita gestionar tareas, es decir, agregar, eliminar y marcar tareas como completadas. Los estudiantes aprenderán cómo estructurar una app en Flutter, cómo gestionar el estado de los widgets y cómo implementar funcionalidades básicas de interacción.

### Requisitos de la actividad

#### Pantalla de inicio:
- Mostrar una lista de tareas.
- Cada tarea debe tener un título, una descripción y un indicador de si está completada o no.

#### Agregar tarea:
- Incluir un botón que permita al usuario agregar una nueva tarea.
- Al presionar el botón, debe abrirse un formulario con campos para ingresar el título y la descripción de la tarea.

#### Eliminar tarea:
- Permitir eliminar una tarea de la lista.
- Puede ser mediante un botón en cada tarea o deslizando la tarea a la izquierda o derecha (funcionalidad estándar en Flutter).

#### Marcar como completada:
- Debe haber un botón o un checkbox para marcar una tarea como completada, lo que cambiará su apariencia (por ejemplo, tacharla o cambiar el color de fondo).

#### Navegación básica:
- Implementar navegación entre pantallas: una para la lista de tareas y otra para agregar tareas.

## Cómo Subir el Código a GitHub

1. Inicializa un repositorio Git en tu proyecto:
   ```sh
   git init
   ```
2. Agrega los archivos al repositorio:
   ```sh
   git add .
   ```
3. Realiza un commit con un mensaje descriptivo:
   ```sh
   git commit -m "Inicialización del proyecto con la actividad de inicio de sesión y gestión de tareas"
   ```
4. Crea un repositorio en GitHub y copia la URL del mismo.
5. Agrega el repositorio remoto:
   ```sh
   git remote add origin <URL_DEL_REPOSITORIO>
   ```
6. Sube el código al repositorio:
   ```sh
   git push -u origin main
   ```

¡Listo! Ahora tu código estará disponible en GitHub.
