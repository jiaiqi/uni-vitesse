<p align='center'>
  <img src='https://user-images.githubusercontent.com/36911513/250519667-0b07fd60-968d-4d81-9185-1e8ac421ab02.png' alt='Uni Vitesse - Opinionated Vite Starter Template' width='800'/>
</p>

<h6 align='center'>
<a href="https://uni-vitesse.netlify.app/">Live Demo</a>
</h6>

<h5 align='center'>
<b>UniAPP version of <a href="https://github.com/antfu/vitesse-lite">Vitesse-lite</a></b>
</h5>

<br/>

<p align='center'>
<a href="https://github.com/jiaiqi/uni-vitesse/blob/master/README.md">简体中文</a> | <b>English</b>
</p>

<br/>

Environment configuration Copy From [Vitesse-lite](https://github.com/antfu/vitesse-lite), Strive for a development experience good environment configuration.

 ## Features

- ⚡️ [Vue 3](https://github.com/vuejs/core), [Vite 3](https://github.com/vitejs/vite), [pnpm](https://pnpm.io/), [ESBuild](https://github.com/evanw/esbuild) - born with fastness

- 🗂 [File based routing](https://github.com/jiaiqi/uni-vitesse/tree/master/src/pages)

- 📦 [Components auto importing](https://github.com/jiaiqi/uni-vitesse/blob/master/src/components)

- 📑 [Layout system](https://github.com/jiaiqi/uni-vitesse/tree/master/src/layouts)

- 🍍 [State Management via Pinia](https://pinia.vuejs.org)

- 🎨 [UnoCSS](https://github.com/unocss/unocss) - The instant on-demand atomic CSS engine.

- 😃 Use icons from any icon sets in [Pure CSS](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

- 🔥 Use the [new `<script setup>` style](https://github.com/vuejs/rfcs/pull/227)

- 📥 [APIs auto importing](https://github.com/antfu/unplugin-auto-import) - use Composition API and others directly

- ✅ Use [Vitest](http://vitest.dev/) for unit and components testing

- 🦾 TypeScript, of course

- 🔒︎ [Lock the pnpm package manager](https://pnpm.io/only-allow-pnpm)

- ☁️ Deploy on [Netlify](https://www.netlify.com/), zero-config

<br>

If there is no cross-end requirement, [Vitesse-lite](https://github.com/antfu/vitesse-lite) is recommended

## Dropped Features from  [Vitesse-lite](https://github.com/antfu/vitesse-lite)

- ~~VueUse~~

## Pre-packed

### UI Frameworks

- [UnoCSS](https://github.com/antfu/unocss) - The instant on-demand atomic CSS engine.

### Icons

- [Iconify](https://iconify.design) - use icons from any icon sets [🔍Icônes](https://icones.netlify.app/)
- [Pure CSS Icons via UnoCSS](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

### Test Framework

- [Vitest](https://github.com/vitest-dev/vitest) - Unit testing powered by Vite

### Plugins

- [`Pinia`](https://pinia.vuejs.org) - Intuitive Vue.js state management library
- [`vite-plugin-uni-pages`](https://github.com/uni-helper/vite-plugin-uni-pages) - file system based routing
- [`vite-plugin-uni-layouts`](https://github.com/uni-helper/vite-plugin-uni-layouts) - layouts for pages
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - Directly use Vue Composition API and others without importing
- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - components auto import
- [`unocss-applet`](https://github.com/unocss-applet/unocss-applet) - UnoCSS applets preset, compatible with the use of 'Attributify Mode' in applets
- [`reactivity-transform`](https://vue-macros.sxzz.moe/features/reactivity-transform.html) - Vue Macros Reactivity Transform standalone package with `reactivityTransform` syntax candy enabled
- [`vite-plugin-vue-devtools`](https://github.com/webfansplz/vite-plugin-vue-devtools) - Designed to enhance the Vue developer experience.

### Coding Style

- Use Composition API with [`<script setup>` SFC syntax](https://github.com/vuejs/rfcs/pull/227)
- [ESLint](https://eslint.org/) with [@antfu/eslint-config](https://github.com/antfu/eslint-config), single quotes, no semi.

## Try it now!

### GitHub Template

[Create a repo from this template on GitHub](https://github.com/jiaiqi/uni-vitesse/generate).

### Clone to local

If you prefer to do it manually with the cleaner git history

```bash
npx degit jiaiqi/uni-vitesse my-uni-app
cd my-uni-app
pnpm i # If you don't have pnpm installed, run: npm install -g pnpm
```

### Checklist

When you use this template, try follow the checklist to update your info properly

- [ ] Change the author name in `LICENSE`
- [ ] Change the project name, description, `appid` in `manifest.json`
- [ ] Change the icon in `public`
- [ ] Clean up the `README` and delete the demo pages and components

Now enjoy your new project! :)

### Run

Refer to uni-app official documentation：[运行、发布uni-app](https://uniapp.dcloud.net.cn/quickstart-cli.html#%E8%BF%90%E8%A1%8C%E3%80%81%E5%8F%91%E5%B8%83uni-app)
