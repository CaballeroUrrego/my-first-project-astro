# My First Project Astro

Proyecto web desarrollado con Astro para mostrar una landing page con secciones de presentación, servicios, galería, contacto y formulario de contacto. Está estructurado para servir contenido estático y también incluye integración con Netlify Functions para manejar notificaciones.

## Descripción

Este proyecto está pensado como una pequeña aplicación web moderna y ligera, utilizando Astro para generar páginas rápidas y optimizadas. La estructura incluye:

- Página principal con hero, información de la empresa, servicios y contacto
- Componentes reutilizables para cada sección
- Estilos y contenido organizados por componentes
- Integración con Netlify para funciones serverless
- Uso de Axios y dependencias de Astro para el desarrollo del sitio

## Requisitos

- Node.js 18 o superior
- npm
- Git (opcional, para clonar y versionar el proyecto)

## Instalación

1. Clona el repositorio o entra a la carpeta del proyecto:

```bash
cd "c:\Users\se302\Documents\PROGRAMACION\my-first-project-astro"
```

2. Instala las dependencias:

```bash
npm install
```

## Ejecución en desarrollo

Ejecuta el proyecto localmente con:

```bash
npm run dev
```

Luego abre en tu navegador:

```text
http://localhost:4321
```
```

Esto normalmente deja disponible:

- Frontend: http://localhost:4321
- Functions: http://localhost:8888

## Estructura principal

```text
/
├── public/
├── src/
│   ├── components/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── netlify.toml
├── README.md
└── .gitignore
```

## Comandos útiles

```bash
npm run dev
npm run build
npm run preview
npm run astro -- --help
```


