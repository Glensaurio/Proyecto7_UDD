# 🍕 Proyecto Fullstack de Ecommerce de Pizzería

Este es un proyecto fullstack de ecommerce para una pizzería. El frontend está desarrollado con **React** utilizando **Vite** y el backend con **Node.js** y **Express**. El proyecto incluye características como autenticación de usuarios, gestión de productos, un carrito de compras y un sistema de pagos integrados con **Stripe**.

### Características Principales
- **Frontend**: Aplicación de React con un diseño responsive y manejo de estado global.
- **Backend**: API RESTful desarrollada con Node.js, Express y conectada a MongoDB Atlas.
- **Autenticación**: Registro e inicio de sesión de usuarios, verificación de tokens JWT.
- **Carrito de Compras**: Añadir, eliminar y gestionar productos en el carrito de compras.
- **Pagos**: Integración con Stripe para procesar pagos.
- **Base de Datos**: MongoDB Atlas para la gestión de productos, usuarios y pedidos.
- **Documentación**: Documentación de la API con Swagger UI.

## 🛠 Tecnologías Utilizadas

### Frontend:
- **React** (con Vite)
- **Axios** para realizar las peticiones HTTP
- **Tailwind CSS** para el diseño
- **Netlify** para el despliegue

### Backend:
- **Node.js** con **Express**
- **MongoDB** (MongoDB Atlas para producción)
- **Mongoose** para modelado de datos
- **JWT** para autenticación de usuarios
- **Stripe** para procesar pagos
- **Swagger** para documentación de la API
- **Railway** para el despliegue del backend

---

## 🚀 Despliegue

### Frontend:
El frontend ha sido desplegado en Netlify y está disponible en la siguiente URL: 

🔗 [Frontend URL - Netlify](https://nombre-de-tu-proyecto.netlify.app)

### Backend:
El backend ha sido desplegado en Railway y está disponible en la siguiente URL:

🔗 [Backend URL - Railway](https://nombre-de-tu-backend.railway.app/api)

> Asegúrate de que el frontend esté configurado para apuntar al backend correcto a través de la variable `VITE_REACT_APP_BACKEND_URL` en el archivo `.env`.

### Base de Datos:
El proyecto está conectado a una base de datos en **MongoDB Atlas**.

---

## 🛠 Instalación y Uso Local

Si deseas ejecutar este proyecto en tu entorno local, sigue los pasos a continuación:

### 1. Clonar el Repositorio:
```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
