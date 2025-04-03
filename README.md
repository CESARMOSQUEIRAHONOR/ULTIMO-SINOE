# SINOE Notificaciones - Aplicación de Gestión

Esta aplicación web permite gestionar notificaciones del Sistema de Notificaciones Electrónicas (SINOE) del Poder Judicial del Perú, automatizando el proceso de descarga, procesamiento y programación de diligencias en Google Calendar.

## Estructura del Proyecto

El proyecto está organizado en varios módulos independientes que trabajan juntos:

- **sinoe-app-frontend**: Interfaz de usuario desarrollada con React y Material-UI
- **sinoe-app-backend**: API REST desarrollada con Node.js y Express
- **sinoe-scraper**: Módulo para iniciar sesión en SINOE y descargar notificaciones
- **pdf-processor**: Módulo para procesar PDFs y extraer información de diligencias
- **calendar-integration**: Módulo para integración con Google Calendar

## Requisitos

- Node.js 14.x o superior
- MongoDB
- Navegador compatible con Puppeteer (Chrome/Chromium)
- Cuenta de Google con acceso a Google Calendar API

## Instalación

1. Clonar este repositorio
2. Instalar dependencias en cada módulo:

```bash
# Instalar dependencias del frontend
cd sinoe-app-frontend
npm install

# Instalar dependencias del backend
cd ../sinoe-app-backend
npm install

# Instalar dependencias del scraper
cd ../sinoe-scraper
npm install

# Instalar dependencias del procesador PDF
cd ../pdf-processor
npm install

# Instalar dependencias de la integración con Calendar
cd ../calendar-integration
npm install
```

## Configuración

1. Configurar variables de entorno en cada módulo según sea necesario
2. Configurar credenciales de SINOE y Google Calendar
3. Configurar rutas de almacenamiento para PDFs

## Ejecución

1. Iniciar el backend:
```bash
cd sinoe-app-backend
npm start
```

2. Iniciar el frontend:
```bash
cd sinoe-app-frontend
npm start
```

## Documentación

Para más información, consulte los siguientes documentos:

- [Arquitectura de la Aplicación](docs/arquitectura_app.md)
- [Documentación Técnica](docs/documentacion.md)
- [Manual de Usuario](docs/manual_usuario.md)

## Licencia

Este proyecto es de uso privado y no está disponible para distribución pública.

## Contacto

Para soporte o consultas, contacte al desarrollador.
