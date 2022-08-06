## Firmament

A derivative of [Spectre](https://github.com/picturepan2/spectre) with extra styles.

### Building

```sh
npm install
npx gulp build
# ^or npx gulp build for a one-off build.
```

The necessary assets will be updated in the `dist` directory.

### Development

We use [browser-sync](https://browsersync.io/) for interactive development. Run `npx gulp serve` to see `dev/index.html` served.
Any changes to source files will trigger a browser reload--changes to `scss` files will rebuild the corresponding `css` files
and inject them into open browser windows.

### Distribution

We currently list it on [`jsdelivr`](https://www.jsdelivr.com/features#gh)

Latest should be available at:

```
https://cdn.jsdelivr.net/gh/chalkandcheese/epistyle/dist/base.min.css
```

Or by commit/tag:

```
https://cdn.jsdelivr.net/gh/chalkandcheese/epistyle@f88df718c6a20dc904d3c694f79b32afae1ad4af/dist/base.min.css
```
