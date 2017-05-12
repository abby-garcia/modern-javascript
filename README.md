<p align='center'>
  <a href="https://mike.works" target='_blank'>
    <img height=40 src='https://assets.mike.works/img/login_logo-33a9e523d451fb0d902f73d5452d4a0b.png' />
  </a> 
</p>
<p align='center'>
  <a href="https://mike.works/course/modern-javascript-437a5c3" target='_blank'>
    <img src='https://cloud.githubusercontent.com/assets/558005/25995673/c8d86ce6-3713-11e7-8a18-9c85bcf73fc9.png' />
  </a>
</p> 

This is the example project used for the [Mike.Works](https://mike.works) [Modern JavaScript](https://mike.works/course/modern-javascript-437a5c3) course.

## What are the pieces?

* [Webpack 2](https://webpack.js.org)
* [TypeScript](https://www.typescriptlang.org) 2.3, setup for experimental decorator support
* [TSLint](https://github.com/palantir/tslint) for linting, setup with a strict JSX-friendly set of rules
* [sass-loader](https://github.com/webpack-contrib/sass-loader) for traditional management of styles
* [Preact](https://github.com/developit/preact) v8 for building components (and [preact-compat](https://github.com/developit/preact-compat) so you can use it as you would use React)
* [Hot Loader v3](https://github.com/gaearon/react-hot-loader) so styles and JS are updated in place as you save source code

## How to use it

##### Start the Development Server

`npm start`

##### Build Development Assets in the `/dist` folder

`npm run build:dev`

##### Build Production Assets in the `/dist` folder

`npm run build:dist`


# Copyright

&copy; 2017 [Mike.Works](https://mike.works), All Rights Reserved

###### This material may not be used for workshops, training, or any other form of instructing or teaching developers, without express written consent

