# svelte-loader

A [webpack](https://webpack.js.org) loader for [svelte](https://svelte.technology).


## Usage

Configure inside your `webpack.config.js`:

```javascript
  ...
  module: {
    rules: [
      ...
      {
        test: /\.(html|svelte)$/,
        exclude: /node_modules/,
        use: 'svelte-loader'
      }
      ...
    ]
  }
  ...
```

Checkout [example setup](./example).


## License

MIT