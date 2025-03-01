# PrismJS Darcula Theme

[![npm](https://img.shields.io/npm/v/prismjs-darcula-theme.svg)](https://www.npmjs.com/package/prismjs-darcula-theme)
[![license](https://img.shields.io/npm/l/prismjs-darcula-theme.svg)](https://www.npmjs.com/package/prismjs-darcula-theme)

A syntax highlighting theme for [PrismJS] based on the Darcula theme from the [JetBrains] IDEs.

## Examples

![Example screenshot](screenshot.png)

Check out more examples and other languages on [GitHub pages](https://lucascorpion.github.io/prismjs-darcula-theme).

## Usage

### HTML

Download and include the compiled stylesheet in the `head` of your html:

```html
<link href="darcula.css" rel="stylesheet" />
```

### Astro

Install the package:

```shell
npm install prismjs-darcula-theme
```

Ensure you are using the `prism` syntax highlighting mode in `astro.config.mjs`:

```js
import { defineConfig } from 'astro/config';

export default defineConfig({
  markdown: {
    syntaxHighlight: 'prism',
  },
});
```

Add this to your component:

```js
import 'prismjs-darcula-theme/darcula.css';
```

### Gatsby

This theme can be used in Gatsby with [gatsby-remark-prismjs].
Install the package using:

```shell
npm install prismjs-darcula-theme
```

Add this import to `gatsby-browser.js`:

```js
import 'prismjs-darcula-theme/darcula.css';
```

## Development

Run `npm run docs:watch` to watch `darcula.scss` for file changes, compiling it to `docs/darcula.css`.
To compile the file without watching for changes, use `npm run docs`.
Open `docs/index.html` in your browser to view the results.

[PrismJS]: https://prismjs.com
[JetBrains]: https://www.jetbrains.com
[gatsby-remark-prismjs]: https://www.gatsbyjs.org/packages/gatsby-remark-prismjs
[gatsby-plugin-sass]: https://www.gatsbyjs.org/packages/gatsby-plugin-sass
