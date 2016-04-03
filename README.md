# Cartridge Sass Legacy[![Build Status](https://travis-ci.org/cartridge/cartridge-sass.svg?branch=master)](https://travis-ci.org/cartridge/cartridge-sass)

**It is recommended to use this instead of [cartridge-sass](https://github.com/cartridge/cartridge-sass) if you require windows compatibility or are other wise having issues running the main Sass module**

> Sass expansion pack for [Cartridge](https://github.com/cartridge/cartridge). This module uses an older version of gulp-sass that works on windows.

To use this module, you will need [cartridge-cli](https://github.com/cartridge/cartridge-cli) installed and have a cartridge project setup.

```shell
npm install cartridge-sass --save-dev
```

This module adds the following to a project:

* Sass compilation using [gulp-sass](https://github.com/dlmanning/gulp-sass)
* Source map generation using [gulp-sourcemaps](https://github.com/floridoo/gulp-sourcemaps) (`local only`)
* Sass import file creation using [gulp-sass-generate-contents](https://github.com/andrewbrandwood/gulp-sass-generate-contents)
* CSS manipulation using [gulp-postcss](https://github.com/postcss/gulp-postcss)
* Automatic CSS vender prefixes using [autoprefixer](https://github.com/postcss/autoprefixer)
* Media query merging using [css-mqpacker](https://github.com/hail2u/node-css-mqpacker)
* CSS minification using [cssnano](https://github.com/ben-eb/cssnano) (`prod only`)
* Conversion of pixels to rems using [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem)

##Config

Once installed, the config file `task.sass.js` is created and stored in the `_config` directory in the root of your cartridge project.

##Using

The [FrontEnd CSS guidelines](https://github.com/code-computerlove/frontend-guidelines/blob/master/FE-guidelines-CSS.md) are a good place to start when beginning your project
