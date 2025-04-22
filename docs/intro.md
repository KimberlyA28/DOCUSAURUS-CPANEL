---
sidebar_position: 1
---

# Introducción al tutorial

Descubramos **Docusaurus en menos de 5 minutos**.

## Primeros pasos

Empieza creando un nuevo sitio web.

O prueba Docusaurus inmediatamente con **[docusaurus.new](https://docusaurus.new)**.

### Qué necesitas

- [Node.js](https://nodejs.org/en/download/) versión 18.0 o superior:
- Al instalar Node.js, se recomienda marcar todas las casillas de verificación relacionadas con las dependencias.

## Generar un nuevo sitio web

Genera un nuevo sitio web de Docusaurus usando la **plantilla clásica**.

La plantilla clásica se añadirá automáticamente a tu proyecto tras ejecutar el comando:

```bash
npm init docusaurus@latest my-website classic
```

Puedes escribir este comando en el Símbolo del sistema, PowerShell, la Terminal o cualquier otra terminal integrada en tu editor de código.

El comando también instala todas las dependencias necesarias para ejecutar Docusaurus.

## Inicia tu sitio

Ejecuta el servidor de desarrollo:

```bash
cd my-website
npm run start
```

El comando `cd` cambia el directorio con el que estás trabajando. Para trabajar con tu sitio de Docusaurus recién creado, deberás acceder a la terminal.

El comando `npm run start` compila tu sitio web localmente y lo sirve a través de un servidor de desarrollo, listo para que lo veas en http://localhost:3000/.

Abra `docs/intro.md` (esta página) y edite algunas líneas: el sitio **se recarga automáticamente** y muestra sus cambios.