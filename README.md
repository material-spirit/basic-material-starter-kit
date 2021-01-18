# Basic Material Starter Kit


:rocket: **Basic template for experimenting and prototyping with [Material Components for the Web](https://material.io/develop/web) (or MDC-Web).**

The template is based on [Getting Started](https://material.io/develop/web/docs/getting-started) doc, but fixes some errors and adds small improvements:

- :heavy_check_mark: fixed outdated `babel-loader` configuration
- :heavy_check_mark: links `Roboto` font
- :heavy_check_mark: proper `mdc-button` HTML markup


**MDC-Web is used with SASS** (not via CDN) allowing you to use mixins, perform customizations and theming. As an example, the template includes customized [@material/button](https://material.io/components/buttons/web) component.


## Usage

Clone the repo, then:

``` bash
# install dependencies
yarn install

# serve with hot reload at localhost:8080
yarn start

# build for production with minification
yarn build
```
