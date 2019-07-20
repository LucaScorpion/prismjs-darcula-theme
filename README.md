# PrismJS Darcula Theme

[![npm](https://img.shields.io/npm/v/prismjs-darcula-theme.svg)](https://www.npmjs.com/package/prismjs-darcula-theme)
[![license](https://img.shields.io/npm/l/prismjs-darcula-theme.svg)](https://www.npmjs.com/package/prismjs-darcula-theme)

A syntax highlighting theme for [PrismJS] based on the Darcula theme from the [JetBrains] IDEs.

## Examples

Check out the [examples on GitHub pages](https://lucascorpion.github.io/prismjs-darcula-theme) for:

- JavaScript
- HTML
- Java
- CSS
- JSON
- YAML

## Usage

### Gatsby

This theme can be used in Gatsby with [gatsby-remark-prismjs]. Simply install the package using:

```shell
npm install prismjs-darcula-theme
```

And add this line in `gatsby-browser.js`:

```js
import 'prismjs-darcula-theme/darcula.css';
```

Alternatively, if you're using [gatsby-plugin-sass] you can use the original SCSS:

```js
import 'prismjs-darcula-theme/darcula.scss';
```

## Development

Run `npm run docs:watch` to watch `darcula.scss` for file changes, compiling it to `docs/darcula.css`. To compile the file without watching for changes, use `npm run docs`. Open `docs/index.html` in your browser to view the results.

[PrismJS]: https://prismjs.com
[JetBrains]: https://www.jetbrains.com
[gatsby-remark-prismjs]: https://www.gatsbyjs.org/packages/gatsby-remark-prismjs
[gatsby-plugin-sass]: https://www.gatsbyjs.org/packages/gatsby-plugin-sass