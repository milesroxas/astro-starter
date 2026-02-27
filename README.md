# Astro Starter

Astro site with React, Tailwind CSS 4, GSAP, and Biome for formatting and linting.

## Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── .vscode/
│   ├── settings.json    # Biome as default formatter, format on save
│   ├── extensions.json  # Recommends Astro and Biome extensions
│   └── launch.json
├── astro.config.mjs     # Astro + React + Tailwind (Vite plugin)
├── biome.json           # Linting, formatting, a11y rules
├── tsconfig.json
└── package.json
```

## Tech Stack

- **Astro** 5.x
- **React** 19 (via `@astrojs/react`)
- **Tailwind CSS** 4 (via `@tailwindcss/vite`)
- **GSAP**
- **Biome** (lint + format)

## Commands

| Command         | Action                                      |
| :-------------- | :------------------------------------------ |
| `pnpm install`  | Install dependencies                        |
| `pnpm dev`      | Start dev server at `localhost:4321`        |
| `pnpm build`    | Build to `./dist/`                          |
| `pnpm preview`  | Preview production build                    |
| `pnpm lint`     | Run Biome check                             |
| `pnpm lint:fix` | Run Biome check and apply fixes             |
| `pnpm format`   | Format files with Biome                     |

## Setup

1. `pnpm install`
2. Install the [Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode) and [Biome](https://marketplace.visualstudio.com/items?itemName=biomejs.biome) extensions when prompted (or from Extensions)
3. `pnpm dev`

## Learn More

[Astro docs](https://docs.astro.build) · [Biome docs](https://biomejs.dev)
