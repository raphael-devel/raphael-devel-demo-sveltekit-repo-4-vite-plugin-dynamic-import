# raphael-devel-demo-sveltekit-repo-4-vite-plugin-dynamic-import

The setup during 'pnpm create svelte@latest my-app' was done as follows:

```
Welcome to SvelteKit!

✔ Which Svelte app template? › SvelteKit demo app
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
  1: cd my-app
  2: npm install (or pnpm install, etc)
  3: git init && git add -A && git commit -m "Initial commit" (optional)
  4: npm run dev -- --open

To close the dev server, hit Ctrl-C

Stuck? Visit us at https://svelte.dev/chat
```

pnpm install 

returned:

```
  ╭──────────────────────────────────────────────────────────────────╮
   │                                                                  │
   │                Update available! 7.5.0 → 7.26.2.                 │
   │   Changelog: https://github.com/pnpm/pnpm/releases/tag/v7.26.2   │
   │              Run "pnpm add -g @pnpm/exe" to update.              │
   │                                                                  │
   │      Follow @pnpmjs for updates: https://twitter.com/pnpmjs      │
   │                                                                  │
   ╰──────────────────────────────────────────────────────────────────╯

Packages: +223
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Packages are cloned from the content-addressable store to the virtual store.
  Content-addressable store is at: /home/scrapper/.local/share/pnpm/store/v3
  Virtual store is at:             node_modules/.pnpm
Progress: resolved 270, reused 200, downloaded 22, added 223, done
node_modules/.pnpm/svelte-preprocess@5.0.1_atrrhq7vg4ekua4nnyrpuardle/node_modules/svelte-preprocess: Running postinstall script, done in 29ms
node_modules/.pnpm/@sveltejs+kit@1.3.2_svelte@3.55.1+vite@4.0.4/node_modules/@sveltejs/kit: Running postinstall script, done in 946ms

devDependencies:
+ @fontsource/fira-mono 4.5.10
+ @neoconfetti/svelte 1.0.0
+ @sveltejs/adapter-auto 1.0.2
+ @sveltejs/kit 1.3.2
+ @types/cookie 0.5.1
+ @typescript-eslint/eslint-plugin 5.49.0
+ @typescript-eslint/parser 5.49.0
+ eslint 8.33.0
+ eslint-config-prettier 8.6.0
+ eslint-plugin-svelte3 4.0.0
+ prettier 2.8.3
+ prettier-plugin-svelte 2.9.0
+ svelte 3.55.1
+ svelte-check 3.0.3
+ tslib 2.5.0
+ typescript 4.9.4
+ vite 4.0.4
+ vitest 0.25.8 (0.28.3 is available)

 WARN  The integrity of 2101 files was checked. This might have caused installation to take longer.
```
