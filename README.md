# mwe

A minimal working example showing a bug with the url of svg `<use>` tag.
In `App.vue`, there are two divs with an svg imported with the same use. But when running the server, the first one is correct, the second one is missing the `#logo` that prevent the browser to know the root element of the SVG.

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
