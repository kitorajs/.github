<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kitorajs/.github/main/profile/readme-header-dark.svg">
    <img alt="Kitora: React UI built from primitives up" src="https://raw.githubusercontent.com/kitorajs/.github/main/profile/readme-header.svg" width="880">
  </picture>
</p>

<p align="center"><strong>React UI built from primitives up.</strong></p>

<p align="center">Headless primitives, styled components and kits for forms, data grids, overlays, drag and drop, docking, windows, editors and charts, for React 19, TypeScript and Tailwind CSS v4: server-component ready, and all on one design language you can switch live.</p>

<p align="center">
  <a href="https://kitorajs.github.io">Website</a> ·
  <a href="https://kitorajs.github.io/docs/getting-started/install">Getting started</a> ·
  <a href="https://kitorajs.github.io/components">Components</a> ·
  <a href="https://kitorajs.github.io/kits">Kits</a> ·
  <a href="https://kitorajs.github.io/docs">Docs</a>
</p>

## Try it now

Kitora is in pre-release: it is not on npm yet and has no version numbers. Until it is stable, the compiled packages install straight from GitHub with pnpm.

**Start from the starter app** (Vite, React, Tailwind CSS v4, TypeScript):

```bash
git clone https://github.com/kitorajs/starter my-app
cd my-app
pnpm install
pnpm dev
```

**Or add the packages to your own app:**

```bash
pnpm add "github:kitorajs/packages#path:/ui" "github:kitorajs/packages#path:/primitives" "github:kitorajs/packages#path:/theme"
```

```tsx
import { Button } from "@kitora/ui/button"
```

The full steps (peer dependencies, the Tailwind stylesheet lines, the pnpm 11 setting, pinning and updating a snapshot) are in the [packages README](https://github.com/kitorajs/packages#readme).

## Repositories

| Repository | What it holds |
| --- | --- |
| [packages](https://github.com/kitorajs/packages) | Every `@kitora/*` package, compiled, one folder per package. Each push is a tagged snapshot. |
| [starter](https://github.com/kitorajs/starter) | A ready app to copy: Vite, React, Tailwind CSS v4 and TypeScript with the packages installed from GitHub. |
| [kitorajs.github.io](https://github.com/kitorajs/kitorajs.github.io) | The built website: docs, every component and kit with live demos. |

## What is inside

- **Primitives:** headless, accessible building blocks with no styling of their own.
- **Components:** styled with Tailwind CSS v4 on top of the primitives, one import per component.
- **Kits:** larger pieces that work together, such as the form engine, data grid, overlays, drag and drop, docking, windows, editors and charts.
- **Design languages:** tokens, component styles and layout presets you can switch live, or replace with your own.

Browse them all with live demos at [kitorajs.github.io](https://kitorajs.github.io). MIT licensed.
