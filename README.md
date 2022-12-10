# Basic Material Starter Kit


:rocket: **Basic template for experimenting and prototyping with [Material Components for the Web](https://material.io/develop/web) (or MDC-Web).**

The template is based on [Getting Started](https://material.io/develop/web/docs/getting-started) doc, but fixes some errors and adds small improvements:

- :heavy_check_mark: fixed outdated `babel-loader` configuration
- :heavy_check_mark: links `Roboto` font
- :heavy_check_mark: proper `mdc-button` HTML markup


**MDC-Web is used with SASS** (not via CDN) allowing you to use mixins, perform customizations and theming. As an example, the template includes customized [@material/button](https://material.io/components/buttons/web) component.


## Usage

### Option 1: Developing locally

Go to [Releases](https://github.com/material-spirit/basic-material-starter-kit/releases) and download the latest release. Unpack it, rename the folder/app and use it as a starting point for experimenting with MDC-Web:
``` bash
# install dependencies
yarn install

# serve with hot reload at localhost:8080
yarn start

# build for production with minification
yarn build
```

### Option 2: Developing and sharing online

1. Go to [codesandbox.io](https://codesandbox.io/) and click Create Sandbox.
2. Select "Import Project" and enter GitHub repository: `https://github.com/material-spirit/basic-material-starter-kit.git`
3. Once the initialization is done, you'll have online workspace ready for development and sharing.
