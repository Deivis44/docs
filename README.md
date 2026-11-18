# Server Rasputin

Documentación de un servidor casero sobre Raspberry Pi 5 de 8 GB. La [introducción](introduction.mdx) describe su propósito: alojar un servidor de Minecraft, compartir archivos y multimedia, y dar acceso remoto a través de una red privada con Tailscale.

## Contenido

| Ruta | Contenido |
| --- | --- |
| [`introduction.mdx`](introduction.mdx) | Resumen del servidor, objetivos y preguntas frecuentes |
| [`docs.json`](docs.json) | Navegación, tema y configuración del sitio |
| [`images/`](images) y [`logo/`](logo) | Recursos visuales |
| [`essentials/`](essentials) y [`api-reference/`](api-reference) | Ejemplos de la plantilla de Mintlify |

El sitio está en desarrollo. Las páginas de ejemplo de la plantilla describen Mintlify y una API de muestra.

## Vista previa local

Con una versión de Node.js compatible con el CLI de Mintlify, ejecuta desde el directorio que contiene `docs.json`:

```bash
npm install -g mint
mint dev
```

La vista previa abre en [`localhost:3000`](http://localhost:3000). Para empezar a editar la documentación del servidor, abre `introduction.mdx`.

[Instalación de Mintlify y requisitos de Node.js](https://www.mintlify.com/docs/cli/install)
