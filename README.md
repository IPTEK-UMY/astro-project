# Project Astro Js

Jika kalian ingin melihat previewnya, bisa langsung copy code dibawah ini!

```sh
git clone https://github.com/IPTEK-UMY/astro-project.git
```

## 🚀 Project Structure

Struktur File dalam project ini (update setiap ada perubahan).

```text
/
├── public/
│   └── favicon.svg
|   |
├── src/
│   ├── components/
│   │   └── Card.astro
│   │   └── BlogPost.astro
│   │   └── Footer.astro
│   │   └── Hamburger.astro
│   │   └── Header.astro
│   │   └── Navigation.astro
│   │   └── Social.astro
│   ├── layouts/
│   │   └── Layout.astro
│   │   └── BaseLayout.astro
│   │   └── MarkdownPostLayout.astro
│   ├── pages/
│   │   └── index.astro
│   │   └── about.astro
│   │   └── blog.astro
│   │   │
│   │   ├── posts/
│   │   │   └── post-1.md
│   │   │   └── post-2.md
│   │   │   └── post-3.md
│   │   │   └── post-4.md
│   │   │   └── post-5.md
│   │   └── tags/
│   │       └── [tag].astro
│   │       └── index.astro
│   ├── scripts/
│   │   └── menu.js
│   └── styles/
│       └── global.css
└── package.json
```

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
