# 🍽️ Dulce & Orden

> SaaS de gestión de inventario y pedidos para cafeterías y restaurantes pequeños.

## 🚀 ¿Qué problema resuelve?

Los restaurantes pequeños controlan su inventario con libretas,
Excel o simplemente de memoria. Esto genera desabasto inesperado,
pérdida de dinero y desorganización operativa.

**Dulce & Orden** permite registrar pedidos de forma digital,
generar tickets automáticamente y descontar los ingredientes
del inventario en tiempo real — sin esfuerzo extra.

## ✨ Funcionalidades principales

- 🧾 Registro de pedidos desde cualquier dispositivo
- 🎟️ Generación automática de ticket digital por pedido
- 📦 Descuento automático de inventario al generar el ticket
- 📊 Dashboard de stock en tiempo real
- 🔔 Alertas cuando un ingrediente está por agotarse
- 🔐 Roles de usuario: administrador, mesero, cocina

## 🛠️ Stack tecnológico

| Capa | Tecnología |
|------|-----------|
| Frontend | React + Tailwind CSS |
| Backend | Node.js + Express |
| Base de datos | PostgreSQL |
| Tiempo real | Socket.io |
| Autenticación | JWT |
| Deploy frontend | Vercel |
| Deploy backend | Railway |
| Control de versiones | GitHub Flow |

## 📁 Estructura del proyecto
dulce-y-orden/
├── client/          # Frontend React
├── server/          # Backend Node.js
├── docs/            # Documentación técnica
└── README.md

## 👥 Equipo

| Nombre | Rol |
|--------|-----|
| Castañeda Sánchez Dana Lizbeth | Product Owner |
| Olaya Gutiérrez Carlos | Tech Lead |
| Montalvo Osorio Alexis | Product Engineer |
| Flores Osorio Jarumi Guadalupe | QA / Delivery |
| Reyes Torres Manelic Alitzel | Growth Lead |

## ⚙️ Instalación local

```bash
# Clonar el repositorio
git clone https://github.com/CharlyLP04/dulce-y-orden.git
cd dulce-y-orden

# Instalar dependencias del servidor
cd server && npm install

# Instalar dependencias del cliente
cd ../client && npm install
```

## 🔀 Flujo de trabajo

Usamos **GitHub Flow**. Ver [`docs/github-flow.md`](docs/github-flow.md)
y [`CONTRIBUTING.md`](CONTRIBUTING.md) antes de hacer cualquier cambio.

## 📌 Tablero del proyecto

[Ver tablero de issues →](https://github.com/CharlyLP04/dulce-y-orden/issues)
