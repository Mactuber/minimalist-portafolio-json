# Minimalist Portfolio / CV Template

Basado en el diseño de Bartosz Jarocki  
Creado por [Mactuber](https://github.com/Mactuber)  

Un portafolio y CV minimalista diseñado para la web y PDF. Personaliza tu contenido usando un archivo JSON compatible con [jsonresume.org](https://jsonresume.org/) y genera una experiencia de alta calidad tanto para impresión como para visualización en navegador.  

### 🛠️ Stack  
- **Astro**: El framework web de la nueva generación.  
- **TypeScript**: JavaScript con tipado estático.  
- **Ninja Keys**: Menú desplegable con atajos de teclado hecho en JavaScript puro.  

---

### 🚀 Empezar  

1. **Usa este repo como plantilla:**  
   Clona este proyecto como base para crear tu propio portafolio/CV.  

   ```bash
   # Activa pnpm en MacOS, WSL & Linux
   corepack enable
   corepack prepare pnpm@latest --activate

# Inicializa el proyecto
pnpm create astro@latest -- --template Mactuber/minimalist-portfolio-json

Personaliza el contenido:
Edita el archivo cv.json para añadir tu información personal y profesional.

# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
