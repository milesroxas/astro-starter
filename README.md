# Astro Starter

Content-driven Astro site with Biome for formatting and linting.

## Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   └── pages/
├── .vscode/
│   ├── settings.json    # Biome as default formatter, format on save
│   └── extensions.json  # Recommends Biome extension
├── biome.json           # Linting, formatting, a11y rules
└── package.json
```

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
2. Install the [Biome extension](https://marketplace.visualstudio.com/items?itemName=biomejs.biome) when prompted (or from Extensions)
3. `pnpm dev`

## Learn More

[Astro docs](https://docs.astro.build) · [Biome docs](https://biomejs.dev)
