# 🛍️ E-commerce TiendaSol

Una **aplicación web de comercio electrónico full-stack** desarrollada como parte del Trabajo Práctico Integrador de la materia Desarrollo de Software (DDS) de la carrera Ingeniería en Sistemas de Información (UTN FRBA).  
El proyecto está organizado como **monorepo** combinando un **backend con Express.js** y un **frontend con React**.

---

## 📌 Descripción del proyecto

E-commerce TiendaSol permite:

- Navegar un catálogo de productos.
- Agregar productos al carrito de compras.
- Gestionar sesiones de usuario desde el frontend.
- Comunicar el frontend y backend usando una **API REST**.
- Facilitar el desarrollo y despliegue de ambas partes en un mismo repositorio.

Tiene una estructura pensada para escalar funcionalidades (roles, ordenes, pagos, etc.) y es ideal para demostrar dominio de desarrollo full-stack moderno.

---

## 🧱 Tecnologías utilizadas

### **Backend**
- **Node.js + Express.js** — Framework web y servidor API.
- **CORS** — Permite comunicación entre frontend y backend.  
- **dotenv** — Manejo de variables de entorno.

### **Frontend**
- **React** (Create React App) — SPA (Single Page Application).
- **React Router** — Navegación por rutas.
- **Axios / Fetch** *(si está presente en el código)* — Para consumo de API REST.

### **General**
- **npm Workspaces** — Monorepo para gestionar frontend y backend desde raíz.  
- **JavaScript (ES6+)** — Lenguaje principal.  
- **CSS** — Estilos y presentación. :contentReference[oaicite:1]{index=1}
---
## 📂 Demo video
https://drive.google.com/file/d/1ISe824452fR1M8vEuz-tz6kXnzODwaKu/view?usp=drive_link

## 📂 Estructura del proyecto

```text
/
├── packages/
│   ├── backend/         # API REST con Express.js
│   └── frontend/        # App React (Create React App)
├── package.json         # Configuración del monorepo
├── README.md            # Documentación del proyecto
└── .env.example         # Ejemplo de variables de entorno
