# ParcialDeReneYDeivis


La aplicación es un sistema de gestión de tareas basado en Firebase, diseñado para proporcionar un endpoint público accesible para realizar operaciones CRUD (Create, Read, Update, Delete).
Características principales:
- Backend: Implementado con Firebase Functions para exponer un API REST.
- Base de datos: Utiliza Firebase Firestore para almacenar las tareas.
- Operaciones: Permite la creación, recuperación, actualización y eliminación de tareas mediante GET, POST, PUT y DELETE.
- Transformación de datos: Convierte las respuestas en objetos Task para una mejor manipulación en el frontend o servicios relacionados.

Guía paso a paso para la ejecución del aplicativo:

1. Configuración de la clave de Firebase
- Copia el contenido del archivo llave[1].txt
- Abre el archivo key.json ubicado en la carpeta db
- Pega la información copiada dentro de key.json y guarda los cambios.
2. Ejecución del aplicativo
- Abre una terminal en el directorio del proyecto.
- Ejecuta el siguiente comando:

node src

Esto iniciará la aplicación y habilitará el acceso al backend.

3. Acceder a la documentación de Swagger UI
- Una vez la aplicación esté corriendo, abre tu navegador.
- Ingresa a la siguiente dirección:
http://localhost:3000/api-docs
Aquí podrás visualizar y probar los endpoints disponibles para la gestión de tareas.
