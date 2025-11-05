# Astro Starter Kit


## 🧞 Comandos

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun dev`             | Starts local dev server at `localhost:4321`      |
| `bun build`           | Build your production site to `./dist/`          |
| `bun preview`         | Preview your build locally, before deploying     |
| `bun astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `bun astro -- --help` | Get help using the Astro CLI                     |


# Instalacion Tailwind 4.1

### 1\. ⚙️ El Comando de Instalación

Ejecuta el siguiente comando en la terminal

```bash
bunx astro add tailwind
```

Este comando instala la integración (`@astrojs/tailwind`) y crea los archivos de configuración (`tailwind.config.mjs`, etc.).

### 2\. Disponibilidad Global

Una vez que el comando haya finalizado, Tailwind CSS está disponible para su uso en toda tu página.

### 3\. Verificacion

Puedes empezar a aplicar las clases de utilidad de Tailwind en tu código:

```astro
<header class="bg-gray-800 text-white p-6 shadow-2xl">
  <h1 class="text-3xl font-bold">Mi Sitio Astro con Tailwind</h1>
</header>
```
-----

¡Hecho\! Aquí tienes la guía README actualizada, centrándose solo en la instalación de la dependencia de Iconos y su uso inmediato con Tailwind.

-----

## Integración de Iconos en Astro

### 1\. 🔌 Instalación de la Dependencia

Ejecuta este comando en la terminal

```bash
bun add astro-icon
```

### 2\. Importacion y uso de la dependencia

Una vez instalada la dependencia, puedes importar y usar el componente `<Icon />` en cualquier lugar de tu proyecto. Tambien puedes ocupar las clases del tailwind (`w-`, `h-`, `text-`) para aplicar estilos directamente.

**Ejemplo**


```astro
---
import { Icon } from "astro-icon";
---
<div class="flex items-center space-x-3 p-4 bg-white shadow-xl rounded-xl">
    <Icon 
        class="w-10 h-10 text-red-600" 
    />
</div>
```
-----

