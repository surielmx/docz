# gatsby-theme-docz

> :warning: This is experimental and subject to breaking changes.

## Installation

```sh
yarn add gatsby gatsby-theme-docz
```

## Usage

```js
// gatsby-config.js
module.exports = {
  __experimentalThemes: [
    {
      resolve: 'gatsby-theme-docz',
    },
  ],
}
```

### Configuration

You can usually set your config using `doczrc.js` file ([see all available](https://github.com/pedronauck/docz/blob/master/core/docz-core/src/config/argv.ts#L54-L103)) or if you want to
set some default options for your theme, you can set `options` on plugin definition.
