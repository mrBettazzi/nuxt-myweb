# nuxt-myweb

Nuxt is an extra tool working on top of Vue.js.
It allows creation of Universal Vue Apps : Client-side apps (*like all Vue apps are*) that can enforce Server-Side-Rendering.

> This walkthrough resumes the [Academind Nuxt Introduction by Max Shwarzmueller](https://www.youtube.com/watch?v=nteDXuqBfn0&app=desktop), published 8 Feb 2018

## Build Setup
* ensure you have **Node.js** and **npm**.
* Install vue-cli and nuxt :
```bash
$ npm install -g vue-cli
$ npm install -g create-nuxt-app
```
* create your application :
```bash
$ npx create-nuxt-app <my-project>
```
* declare :
> * the **server framework** you're going to use (none == Node)
> * the **UI framework** you're going to use (boostrap, bulma, element-ui, ..)
> * the **rendering mode** (Universal, SPA)
> * **additional** modules (axios, eslint, ...)
> * **package** mgr (npm, yarn)

* once the project is created, get started with hot reload at localhost:3000 :
```bash
$ cd <my-project>
$ npm install # Or yarn install
$ npm run dev
```
* To build for production and launch server :
```bash
$ npm run build
$ npm start
```
* Check directory structure, and in particular the *./pages* folder. 
* The `index.vue` file here starts the show at `http://localhost:3000`.
* Every `<name>.vue` file here represents a **route** and can be reached at `http://localhost:3000/name`.
* directory hierarchy is matched in the URI. Being `index.vue` the **default route**, A `./pages/<name>.vue` behaves the same as `./pages/<name>/index.vue`.
* In every directory Nuxt puts a `README.md` file

* To generate a static project :
```bash
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).
