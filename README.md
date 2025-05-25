# PyDocs

[![Built with Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build)

PyDocs is a modern, open-source documentation site for learning Python from scratch to advanced topics.  
It is built with [Astro](https://astro.build/) and [Starlight](https://starlight.astro.build/), and organized by key themes for easy navigation and contribution.

![PyDocs](https://nelson-5553.vercel.app/img/Projectos/pydocs.png)
---

## 📚 Features

- **Step-by-step Python learning:** From basics to advanced, with clear examples and exercises.
- **Modern, multi-language documentation:** Spanish and English support.
- **Open Source:** Community-driven, easy to contribute.
- **Fast search and navigation:** Quickly find any topic or function.
- **Beautiful, responsive design:** With light and dark mode.

---

## 🚀 Project Structure

Inside of your Astro + Starlight project, you'll see the following folders and files:

```
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   ├── docs/
│   └── content.config.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name.

Images can be added to `src/assets/` and embedded in Markdown with a relative link.

Static assets, like favicons, can be placed in the `public/` directory.

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

Check out [Starlight’s docs](https://starlight.astro.build/), read [the Astro documentation](https://docs.astro.build), or jump into the [Astro Discord server](https://astro.build/chat).
