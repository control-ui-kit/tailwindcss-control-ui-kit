# tailwindcss-control-ui-kit

This plugin adds tailwind utility classes required for [Control UI Kit](https://github.com/control-ui-kit/control-ui-kit)

## Install

```
npm install --save-dev @control-ui-kit/tailwindcss-control-ui-kit
```

In your `tailwind.config.js` file, load the plugin:

```
module.exports = {
  purge: false,
  theme: {},
  variants: {},
  plugins: [
    require('@control-ui-kit/tailwindcss-control-ui-kit'),
  ],
}
```