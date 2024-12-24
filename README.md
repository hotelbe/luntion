# Tauri + Vue3 + TypeScript

[![Tauri](https://img.shields.io/badge/Platform-Tauri-ffc032)](https://tauri.app/)
[![Vue3](https://img.shields.io/badge/Framework-Vue3-42b883)](https://vuejs.org/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Develop-Vite-747bff)](https://vitejs.dev)
[![Pinia](https://img.shields.io/badge/Store-Pinia-f7d336)](https://pinia.vuejs.org)
[![Unocss](https://img.shields.io/badge/CSS-Unocss-858585)](https://uno.antfu.me/)


This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's Take Over mode by following these steps:

1. Run `Extensions: Show Built-in Extensions` from VS Code's command palette, look for `TypeScript and JavaScript Language Features`, then right click and select `Disable (Workspace)`. By default, Take Over mode will enable itself if the default TypeScript extension is disabled.
2. Reload the VS Code window by running `Developer: Reload Window` from the command palette.

You can learn more about Take Over mode [here](https://github.com/johnsoncodehk/volar/discussions/471).

Template created! To get started run:

```bash
cd luntion
pnpm install
pnpm tauri android init
pnpm tauri ios init
```

For Desktop development, run:

```bash
pnpm tauri dev
```

For Android development, run:

```bash
pnpm tauri android dev
```

For iOS development, run:

```bash
pnpm tauri ios dev
```

For Desktop build, run:

```bash
cargo tauri build
```


## Develop

### Install Tauri && tauri-bundler

See Tauri official: [docs](https://tauri.app/v1/guides/)

### Project setup

```bash
pnpm install
```

### Compiles and hot-reloads for development

```bash
pnpm run tauri dev
```

### Compiles and minifies for production

```bash
pnpm run tauri build
```
