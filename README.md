# Clam.css

Clam.css provides a good-enough set of styles to kick off your new project. It's meant for building prototypes, where you want to build stuff quickly instead of wrestling with CSS. It styles plain HTML, so you don't need to learn a new framework or remember any class names.

Clam.css is also mobile responsive and has a dark mode which follows your system's theme. If you found a bug or have a feature request, please [create an issue on GitHub](https://github.com/rmrt1n/clam.css/issues).

## Quick start

Clam.css is a single CSS file, so to use it you just need to include it in your HTML file. You can do this by including it from a CDN or by installing it from NPM. You can also download the source code directly and put it in your project.

### Straight from the CDN

The simplest way to use Clam.css is to include it directly from the CDN. Just copy the code below and paste it in the `<head>` of your HTML file. Clam.css uses [modern normalize](https://github.com/sindresorhus/modern-normalize) for normalization, so you should include it as well.

```html
<link rel="stylesheet" href="https://unpkg.com/modern-normalize" />
<link rel="stylesheet" href="https://unpkg.com/clam.css" />
```

### Install from NPM

Another option is to install Clam.css from NPM using your preffered package manager (npm, yarn, pnpm, bun, etc.).

```shell
pnpm add clam.css
```

Usage might depend on the javascript framework you're using. In Next.js, you can add this line to your root layout:

```js
import "clam.css";
```

## Documentation

You can find more information on the list of styles Clam.css provides and theming options in [the docs](https://ryanmartin.me/clam.css).

## License

Distributed under the MIT License. See [LICENSE](/LICENSE) for more information.
