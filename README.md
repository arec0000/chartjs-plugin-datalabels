<p align="center">
  <img src="docs/.vuepress/public/hero-title.svg?sanitize=true">
</p>

<p align="center">
  <a href="https://chartjs-plugin-datalabels.netlify.app/guide/getting-started.html"><img src="https://img.shields.io/github/release/chartjs/chartjs-plugin-datalabels.svg?style=flat-square&maxAge=600" alt="Downloads"></a>
  <a href="https://travis-ci.org/chartjs/chartjs-plugin-datalabels"><img src="https://img.shields.io/travis/chartjs/chartjs-plugin-datalabels.svg?style=flat-square&maxAge=600" alt="Builds"></a>
  <a href="https://codeclimate.com/github/chartjs/chartjs-plugin-datalabels"><img src="https://img.shields.io/codeclimate/c/chartjs/chartjs-plugin-datalabels.svg?style=flat-square&maxAge=600" alt="Coverage"></a>
  <a href="https://github.com/chartjs/awesome"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
</p>

## Important Notice

**This is a fork of the original package and it's not supported by the official developers of [chartjs-plugin-datalabels.](https://www.npmjs.com/package/chartjs-plugin-datalabels)**

#### New features:
- Border style customization:
  - `borderDash` — dash pattern, similar to the [`setLineDash()`](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/setLineDash) method of the Canvas 2D API
  - `borderDashOffset` — adjust the offset of the dash pattern, similar to the [`lineDashOffset`](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineDashOffset) property of the Canvas 2D API
  - `borderCap` — similar to the [`lineCap`](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineCap) property of the Canvas 2D API
- Text decoration, you can add flexibly customizable underlines, overlines, or strikethrough lines:
  - `placement` — position of the line ('underline', 'overline', 'line-through')
  - `color` (defaults to the datalabel color)
  - `thickness`
  - `length` (you can provide a function that uses the text width to calculate the length)
  - `offset` — vertical offset in px
  - `dash` — dash pattern, similar to the [`setLineDash()`](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/setLineDash) method of the Canvas 2D API
  - `dashOffset` — adjust the offset of the dash pattern, similar to the [`lineDashOffset`](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineDashOffset) property of the Canvas 2D API
  - `lineCap` — similar to the [`lineCap`](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineCap) property of the Canvas 2D API

New features are still being tested and may not be fully functional yet.

I plan to submit these changes as a pull request to the official chartjs-plugin-datalabels package in the future.

## Overview

Highly customizable [Chart.js](https://www.chartjs.org/) plugin that displays labels on data for any type of charts.

Requires [Chart.js](https://github.com/chartjs/Chart.js/releases) **3.x** or higher.

## Documentation

- [Introduction](https://chartjs-plugin-datalabels.netlify.app/guide/)
- [Getting Started](https://chartjs-plugin-datalabels.netlify.app/guide/getting-started.html)
- [Options](https://chartjs-plugin-datalabels.netlify.app/guide/options.html)
- [Labels](https://chartjs-plugin-datalabels.netlify.app/guide/labels.html)
- [Positioning](https://chartjs-plugin-datalabels.netlify.app/guide/positioning.html)
- [Formatting](https://chartjs-plugin-datalabels.netlify.app/guide/formatting.html)
- [Events](https://chartjs-plugin-datalabels.netlify.app/guide/events.html)
- [TypeScript](https://chartjs-plugin-datalabels.netlify.app/guide/typescript.html)
- [Migration](https://chartjs-plugin-datalabels.netlify.app/guide/migration.html)
- [Samples](https://chartjs-plugin-datalabels.netlify.app/samples/)

## Development

You first need to install node dependencies (requires [Node.js](https://nodejs.org/)):

```
> npm install
```

The following commands will then be available from the repository root:

```
> npm run build            // build dist files
> npm run build:dev        // build and watch for changes
> npm run test             // run all tests and generate code coverage
> npm run test:dev         // run all tests and watch for changes
> npm run lint             // perform code linting
> npm run lint -- --fix    // automatically fix linting problems
> npm run docs             // generate documentation (`dist/docs`)
> npm run docs:dev         // generate documentation and watch for changes
```

## License

`chartjs-plugin-datalabels` is available under the [MIT license](LICENSE.md).
