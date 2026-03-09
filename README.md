# 🚗 Volantia — Plataforma P2P de Renta de Vehículos

Volantia es una plataforma peer-to-peer que conecta a propietarios de autos con personas que necesitan rentar un vehículo. Desarrollada en equipo como proyecto final del bootcamp Henry, con arquitectura fullstack y flujo de pago real integrado.

![Tech Stack](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3-38bdf8?style=flat-square&logo=tailwindcss)
![Auth0](https://img.shields.io/badge/Auth0-autenticación-eb5424?style=flat-square&logo=auth0)
![Mercado Pago](https://img.shields.io/badge/Mercado_Pago-pagos-009ee3?style=flat-square)

[![Demo](https://img.shields.io/badge/Ver_demo-live-brightgreen?style=flat-square)](https://front-pf-henry.vercel.app)

---

## ✨ Funcionalidades

- 🔍 Catálogo de vehículos con filtrado por transmisión, combustible, asientos y precio
- 🚘 Vista de detalle de vehículo con disponibilidad y reserva de fechas
- 💳 Pasarela de pago completa con Mercado Pago (flujos de éxito, pendiente y fallo)
- 👤 Autenticación con Auth0 y Google OAuth
- 📋 Dashboard de usuario con historial de rentas y actividad
- ⭐ Sistema de reseñas al finalizar una reservación
- 🛡️ Protección de rutas para usuarios autenticados
- 📸 Carga de imágenes de vehículos con Cloudinary
- 📱 Diseño responsive con Tailwind CSS

---

## 🛠️ Stack Tecnológico

| Área | Tecnología |
|------|-----------|
| Frontend | Next.js 15 (App Router), React, TypeScript |
| Estilos | Tailwind CSS |
| Autenticación | Auth0, Google OAuth |
| Pagos | Mercado Pago |
| Imágenes | Cloudinary |
| Backend | Railway (API REST) |
| Metodología | SCRUM |

---

## 👩‍💻 Mi rol como Frontend Developer

Este fue un proyecto de equipo. Mis contribuciones principales fueron:

- Diseño de la interfaz y prototipado en Figma
- Renderizado y filtrado del catálogo de vehículos
- Formulario para publicar nuevos vehículos
- Integración completa de la pasarela de pagos con Mercado Pago (incluyendo páginas de éxito, pendiente y fallo)
- Sistema de reseñas al finalizar una reservación
- Documentación técnica del frontend
- Gestión de tareas y coordinación del equipo con SCRUM

---

## 🚀 Instalación y uso local

### Prerrequisitos
- Node.js 18+
- Cuenta en Auth0, Mercado Pago y Cloudinary para las variables de entorno

```bash
npm install
npm run dev
```

### Variables de entorno (`.env.local`)

```env
NEXT_PUBLIC_API_URL=https://tu-backend.railway.app
NEXT_PUBLIC_AUTH0_DOMAIN=tu-dominio.auth0.com
NEXT_PUBLIC_AUTH0_CLIENT_ID=tu-client-id
NEXT_PUBLIC_MP_PUBLIC_KEY=tu-clave-publica-mercadopago
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=tu-cloud-name
```

---

## 👥 Equipo

Proyecto desarrollado en equipo durante el bootcamp Henry (oct–nov 2025).  
**Jenifer Villanueva** — Frontend Developer  
[LinkedIn](https://www.linkedin.com/in/jenifer-villanueva) · [GitHub](https://github.com/JeniferVM)
