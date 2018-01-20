# Chrome Extension Webpack Boilerplate

[![Maintainability](https://api.codeclimate.com/v1/badges/53fe1760e70ec88b641b/maintainability)](https://codeclimate.com/github/nitish173/chrome-extension-webpack-boilerplate/maintainability)

A boilerplate for chrome extensions development with webpack.

Getting started: 
1. Clone the repo and in root do an `npm install` to install the dependencies.
2. Run `npm build-watch` to get the build in `watch` mode.
3. In developer mode in Chrome browser, load the build folder as unpacked extension to see the boilerplate in action.

Notes:
1. Check out the manifest file for the permissions and extension configurations you need.
2. By default, boilerplate comes with a  `browser action`, a `background` page and an `options` page. To add more scripts, for examples, `content scripts` you may add more entry points in webpack configurations.

Besides raising issues/PRs, please feel free to send suggestions for improvements: nitish17312@gmail.com.
Or tweet to https://twitter.com/nitish_173.