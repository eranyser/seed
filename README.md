On-going Seed
===================
On-going seed project.

# Release 01
This first seed includes:

 1. Webpack - the simplest way to use webpack.
 2. typescript loader
 3. css & scss loaders

Loaders are those things that transfer our code from one thing to another.

# Useful Links

> those are useful links:

What is webpack
  - [Webpack 2 Official Site](https://webpack.js.org/)

Installation & Getting Started
  - [Getting Started Guide](https://webpack.js.org/guides/getting-started/)

Webpack Loaders
  - [CSS Loader](https://webpack.js.org/guides/asset-management/)
  - [Sass/SCSS Loader](https://webpack.js.org/loaders/sass-loader/)

I've just created a release branch. In addition I want to create a release.
You can find what is a release [here](https://help.github.com/articles/creating-releases/)

Release 02
==========
In this release I want to copy the ***index.html*** file from the *src* directory to the *dist* directory
For this reason we use: [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin)

A good explanation Video by Mirko Nasato of how to use this loader can be found [here](https://www.youtube.com/watch?v=lPhZW8ZyUA4&list=PLgGUMhSgtxJyIQ4vI3BzlCzZLHL79Ew6p&index=5) and also in Stack-Overflow [here](https://stackoverflow.com/questions/32155154/webpack-config-how-to-just-copy-the-index-html-to-the-dist-folder/34925111)

Release 03
=========
In this release I am upgrading the current code:

 1. Importing a *Person* Object in index.ts from module.ts file to see that typescript is working.
 2. adding a watch script in webpack.config.js
 3. adding resolve extentions in webpack.config.js
