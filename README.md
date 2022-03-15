# swissmation.com Website

(c) 2022 swissmation

## Was wir nutzen

- SvelteKit
- TailwindCSS
- Kein Headless CMS (contentful, anity), sondern MDX lokal

## Sollte beinhalten

- [ ] Design (Farben, Schrift)
- [x] Font
- [ ] Favicons
- [ ] Head (description, title, language, meta)
- [ ] Sitemap
- [x] Robots
- [ ] Error page
- [x] Tracking
- [ ] Slogan
- [ ] Homepage
- [ ] Impressum / Legal
- [ ] Kontakt Seite
- [ ] Cookies
- [ ] SEO (jede Seite, Aufbau & Meta)
- [ ] Mehrsprachigkeit
- [ ] Menu / Navigation
- hover on bilder zoomen
- neuste errungenschaften


## Installation

### Sveltekit (Typescript)

```
npm init svelte@next .
npm install
```

### Tailwind
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init tailwind.config.cjs -p
mv postcss.config.js postcss.config.cjs
npm install -D prettier prettier-plugin-tailwindcss
```
tailwind config


.prettierrc config
"svelteBracketNewLine": false
.vscode/settings

### Font

```
npm i -D "@fontsource/montserrat"
```

add as first lines in app.css
```
@import "@fontsource/montserrat/400.css";
@import "@fontsource/montserrat/700.css";
```

tailwind.config.cjs
```
const defaultTheme = require('tailwindcss/defaultTheme')

module.exports = {
  content: ['./src/**/*.{html,js,svelte,ts}'],
  theme: {
    extend: {
      fontFamily: {
        'sans': ['Montserrat', ...defaultTheme.fontFamily.sans]
      },
    },
  },
  plugins: [],
}
```

## Update

```
npx npm-check-updates -u  
npm install
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## Knowledge
[Schönes Kontakt Formular](https://www.dreipol.ch/kontakt)

[Env Vars in Svelte](https://timdeschryver.dev/blog/environment-variables-with-sveltekit)
[Flowbite Tailwind Components](https://flowbite.com/docs/components/alerts/)
[Tailwind Buttons](https://tailwind-starter-kit.vercel.app/docs/buttons)

[Slider](https://codepen.io/safwendr/pen/LYRWoey)
[One Line Hacks](one-line-hacks)

- Design 
https://www.connorrothschild.com
https://stackblitz.com
https://flayks.com
https://files.community
https://fantinel.dev/#experience
https://awesome-svelte-kit.netlify.app
https://codepen.io/innersociety/pen/rEXoer
https://urara-demo.netlify.app

gradient https://hypercolor.dev

https://animejs.com

tailwind blurry background animation https://www.youtube.com/watch?v=Tmkr2kKUEgU
https://tailwindcss.com/docs/mix-blend-mode
https://tailwindcss.com/docs/cuhttps://hypercolor.dev

gradient https://tailwindcss.com/docs/gradient-color-stops


making a blog https://www.delphic.top/blog/making_a_blog_website_with_sveltekit

svelte body class https://github.com/sveltejs/svelte/issues/3105

signup https://codepen.io/safwendr/pen/LYRWoey

sitemap