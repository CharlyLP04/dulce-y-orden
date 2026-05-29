# 🍔 Burger & Orden

> SaaS de gestión de comandas, inventario crítico y personalización de pedidos diseñado para negocios de hamburguesas y comida rápida de alta rotación.

## 🚀 ¿Qué problema resuelve?

Los negocios de hamburguesas y *fast food* operan bajo una alta carga de estrés en horas pico. La toma de pedidos manual o verbal provoca que las personalizaciones críticas de los clientes (*"sin cebolla"*, *"extra tocino"*, *"término de la carne"*) se lean o escuchen mal en la cocina, generando mermas de comida, retrasos en la parrilla y clientes insatisfechos. Además, la falta de control visual del inventario provoca desabastos imprevistos de insumos clave (como pan brioche o carne) a mitad del servicio nocturno.

**Burger & Orden** centraliza la operación: permite capturar pedidos con especificaciones detalladas desde el celular del mesero, genera tickets digitales automáticos para el parrillero en tiempo real y descuenta los insumos críticos del inventario al instante para prevenir desabastos.

## ✨ Funcionalidades principales

Pendientes 


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

```text
burger-y-orden/
├── client/          # Frontend React (Interfaz de captura y pantalla de cocina)
├── server/          # Backend Node.js (API de pedidos, estados e inventarios)
├── docs/            # Documentación técnica, minutas y guías de validación
└── README.md        # Guía principal del proyecto3


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
