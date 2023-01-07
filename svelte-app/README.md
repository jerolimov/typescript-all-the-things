# svelte-app

* https://svelte.dev
* https://svelte.dev/docs#getting-started
* [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).
* To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## Requirements

* @sveltejs/kit@1.0.7 requires Node ^16.14 || >=18

## Setup

```bash
➜  npm create svelte@latest

create-svelte version 2.1.0

Welcome to SvelteKit!

✔ Where should we create your project?
  (leave blank to use current directory) … svelte-app
✔ Which Svelte app template? › Skeleton project
✔ Add type checking with TypeScript? › Yes, using TypeScript syntax
✔ Add ESLint for code linting? … No / Yes
✔ Add Prettier for code formatting? … No / Yes
✔ Add Playwright for browser testing? … No / Yes
✔ Add Vitest for unit testing? … No / Yes

Your project is ready!
✔ Typescript
  Inside Svelte components, use <script lang="ts">
✔ ESLint
  https://github.com/sveltejs/eslint-plugin-svelte3
✔ Prettier
  https://prettier.io/docs/en/options.html
  https://github.com/sveltejs/prettier-plugin-svelte#options
✔ Vitest
  https://vitest.dev

Install community-maintained integrations:
  https://github.com/svelte-add/svelte-adders

Next steps:
  1: cd svelte-app
  2: npm install (or pnpm install, etc)
  3: git init && git add -A && git commit -m "Initial commit" (optional)
  4: npm run dev -- --open
```

## Available script

* npm run dev
* npm run dev -- --open
* npm run build
* npm run preview
* npm run check
* npm run test:unit
* npm run lint
* npm run format

## Dependencies

* svelte
* sveltejs/adapter
* sveltejs/kit
* eslint
* prettier
* typescript and tslib
* vite
* vitest

## Project structure

```
* src
* static
.eslintignore
.eslintrc.cjs
.npmrc
.prettierignore
.prettierrc
package.json
svelte.config.js
tsconfig.json
vite.config.ts
```
