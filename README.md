# Task Points App

Frontend para una aplicación de estimación de tareas (app tipo planning poker). Desarrollada en React con Vite.

Este proyecto se conecta con el backend [`task-points-api`](https://github.com/jcarlosab/task-points-api) mediante Socket.IO.

## Funcionalidades

- Crear salas para estimar tareas con tu equipo.
- Escoger cartas de puntos (escala Fibonacci).
- Ver resultados en tiempo real.

## Configuración

1. Crea un archivo `.env` en la raíz del proyecto con la siguiente variable:
VITE_API_URL=http://localhost:3000

2. Instala las dependencias:
npm install

3. Inicia el servidor de desarrollo:
npm run dev
