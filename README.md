# Proyecto Backend - Entrega 1

Este proyecto es una API RESTful desarrollada con Node.js, Express y MongoDB para la gestión de usuarios, mascotas y adopciones. Incluye autenticación, manejo de sesiones, generación de datos mock para pruebas y rutas protegidas.

## Funcionalidades principales

- CRUD de usuarios y mascotas
- Gestión de adopciones
- Autenticación y manejo de sesiones con cookies
- Generación de datos mock para pruebas usando Faker
- Estructura modular con controladores, servicios y rutas

## Instalación

1. Clona el repositorio.
2. Ejecuta `npm install` para instalar las dependencias.
3. Configura las variables de entorno si es necesario.
4. Inicia el servidor con `npm start` o `node src/app.js`.

## Uso

- Las rutas principales están bajo `/api/users`, `/api/pets`, `/api/adoptions`, `/api/sessions` y `/api/mocks`.
- Puedes generar datos de prueba enviando un POST a `/api/mocks/generateData` con un JSON como `{ "amount": 10 }`.

## Tecnologías

- Node.js
- Express
- MongoDB & Mongoose
- Faker.js

## Autor

Rodrigo - CoderHouse Backend 3