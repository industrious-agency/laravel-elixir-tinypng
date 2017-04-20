# laravel-elixir-tinypng

Original package by [Kffein](https://github.com/kffein/kffein-elixir-tinypng), forked by [Industrious](https://www.industrious.agency).

## Instructions

1. Go to (Tinypng)[https://tinypng.com/developers] and generate an API Key
2. In your `gulpfile.js`, specify the API key and any folder options in the following format:

```javascript
elixir.config.img = {
  folder: elixir.config.assetsPath + '/img',
  outputFolder: elixir.config.publicPath + '/img',
  tinypngKey: 'APIKEY'
};
```