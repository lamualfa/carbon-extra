<h1 align="center">
  <code>@carbon-extra/css</code>
</h1>

<p align="center">
  Compiled version of <a href="https://github.com/carbon-design-system/carbon/tree/main/packages/styles"><code>@carbon/styles</code></a>. So you don't have to install <code>sass</code> again.
</p>

## Install

###### Using PNPM

```bash
pnpm add @carbon-extra/css
```

###### Using NPM

```bash
npm i @carbon-extra/css
```

###### Using Yarn

```bash
yarn add @carbon-extra/css
```

## Usage

### Self-Hosted

###### Using CSS

```css
@import 'node_modules/@carbon-extra/css/dist/index.css';
```

###### Using Javascript or Typescript

```js
import '@carbon-extra/css'
```

###### Using HTML Link Stylesheet

```html
<link rel="stylesheet" href="node_modules/@carbon-extra/css/dist/index.css">
```

### CDN

###### Using JSDelivr

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@carbon-extra/css/dist/cdn/full.css">
```

###### Using UNPKG

```html
<link rel="stylesheet" href="https://www.unpkg.com/@carbon-extra/css/dist/cdn/full.css">
```

## Structures

| File name                 | Description                         | Status |
| ------------------------- | ----------------------------------- | ------ |
| `full.css`                | Self-hosted, Minified & All themes  | ✅      |
| `cdn/full.css`            | CDN, Minified & All themes          | ✅      |
| `unminified/full.css`     | Self-hosted & All themes            | ✅      |
| `unminified/cdn/full.css` | CDN & All themes                    | ✅      |
| `white.css`               | Self-hosted, Minified & White theme | ⏳      |
| `g10.css`                 | Self-hosted, Minified & G10 theme   | ⏳      |
| `g90.css`                 | Self-hosted, Minified & G90 theme   | ⏳      |
| `g100.css`                | Self-hosted, Minified & G100 theme  | ⏳      |

**Note**

> Use **Self-hosted** version if you use module bundler like Webpack, Rollup, etc. Otherwise, use the **CDN** version instead.