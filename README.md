# WikiGestor - Auth Service

Este microservicio maneja el registro, login y autenticación de usuarios con JWT para la aplicación WikiGestor.

## Tecnologías usadas

- Node.js
- Express
- MongoDB Atlas
- JSON Web Tokens (JWT)
- Swagger para documentación de la API

## Endpoints principales

- `POST /auth/register` - Registrar usuario nuevo
- `POST /auth/login` - Iniciar sesión y obtener token JWT
- `GET /auth/me` - Información del usuario autenticado (requiere token)

## Variables de entorno

- `PORT` - Puerto donde corre el servicio (ejemplo: 3001)
- `MONGODB_URI` - URL de conexión a MongoDB Atlas
- `JWT_SECRET` - Clave secreta para firmar y verificar tokens JWT

## Cómo ejecutar el servicio localmente

1. Instalar dependencias:

bash
npm install

