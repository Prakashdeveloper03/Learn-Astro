# Learn Astro

![typescript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)
![sass](https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white)
![markdown](https://img.shields.io/badge/MDX-1B1F24?logo=mdx&logoColor=white)
![astro](https://img.shields.io/badge/Astro-F55B23?logo=astro&logoColor=white)
![vscode](https://img.shields.io/badge/Visual_Studio_Code-0078D4?logo=visual%20studio%20code&logoColor=white)

This is a demo website to learn Astro.

## Installation

Clone the repository using `git`

```
git clone https://github.com/Prakashdeveloper03/Learn-Astro.git
```

Change to the cloned directory

```
cd <directory_name>
```

To install all requirement packages for the application

```
pnpm i
```

Then, Run the application

```
pnpm run dev
```

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── astro.config.mjs
├── package.json
├── pnpm-lock.yaml
├── public
│	 └── favicon.svg
├── README.md
├── src
│	 ├── components
│	 │	 ├── Card.astro
│	 │	 ├── Features.astro
│	 │	 ├── Footer.astro
│	 │	 ├── Header.astro
│	 │	 ├── Showcase.astro
│	 │	 └── Tabs.astro
│	 ├── env.d.ts
│	 ├── layouts
│	 │	 └── Layout.astro
│	 ├── pages
│	 │	 ├── about.astro
│	 │	 ├── blog.astro
│	 │	 ├── index.astro
│	 │	 └── [slug].astro
│	 ├── posts
│	 │	 ├── astro-1-0.md
│	 │	 ├── astro-1-0-release-update.md
│	 │	 └── astro-on-netlify-edge-functions.md
│	 ├── static
│	 │	 └── images
│	 │	     ├── deploy-logos.png
│	 │	     ├── deploy-logos-small.png
│	 │	     ├── framework-logos.png
│	 │	     ├── framework-logos-small.png
│	 │	     ├── logo.svg
│	 │	     └── screen.png
│	 └── styles
│	     └── global.sass
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                    | Action                                           |
| :------------------------- | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |
