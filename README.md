# gatsby-plugin-styled-jsx-postcss

A Gatsby plugin to use styled-jsx with PostCSS.

## Install

With Yarn:

```bash
yarn add gatsby-source-salsify
```

Or with npm:

```bash
npm install --save gatsby-source-salsify
```

## Usage

```javascript
// In your gatsby-config.js
plugins: [
	'gatsby-plugin-styled-jsx-postcss',
]
```

## Adding PostCSS plugins

This plugin uses the postcss-load-plugins, so you can import PostCSS plugins with any of the [methods mentioned in their documentation](https://github.com/michael-ciniawsky/postcss-load-plugins).