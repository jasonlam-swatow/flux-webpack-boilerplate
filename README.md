flux-webpack-boilerplate
===============

[中文版](#概覽)

## Overview

This is a boilerplate for [Flux](https://facebook.github.io/flux/) and [Webpack](https://webpack.github.io/) workflow of my best practice.

The Flux application part was coded by [@kenwheeler](https://twitter.com/ken_wheeler) for the tutorial: [Create a Shopping Cart Using React.js and Flux](https://scotch.io/tutorials/creating-a-simple-shopping-cart-with-react-js-and-flux). I used it as a simple Flux boilerplate, but the highlight of this project is all about Webpack workflow. You can use it as a seed project to build your own Flux app.

This boilerplate has features as below so far:

* Up-to-date React **v0.14** migrated, including seperated ReactDOM package and tons of new features as well as deprecations. Please check out the upgrade guide of [v0.14](https://facebook.github.io/react/blog/2015/10/07/react-v0.14.html).
* **Webpack** bundler.
* **Babel** instead of JSX transformer introduced.
* **Webpack-dev-server** serving and hot swapping.
* **React-hot-loader** livereload.
* **Uglifying** the bundled JavaScript.
* Preprocessing styles in **Sass**. Required resources such as images and font files are bundled altogether into JavaScript. *Note that I use .woff font format and it is transpiled into inline base64 string.*

## Install

1. Make sure you have *npm* and maybe *webpack* installed globally.
2. Download [zip](https://github.com/jasonlam0619/flux-webpack-boilerplate/archive/master.zip) or `git clone git@github.com:jasonlam0619/flux-webpack-boilerplate.git` onto your computer.
3. `cd flux-webpack-boilerplate-master`
4. `npm install`
5. `npm start` to build the bundle with Webpack, and power the server.
6. Visit `localhost: 8080`.

## Outlook

There will be plenty adjustments in the future. Below are those in the picture:
 
* ES2015 (ECMAScript 6) migration.
* File-loader for Webpack.

***

## 概覽

這是我本人至目前爲止最佳實踐的 Flux + Webpack 工作流模範項目。

Flux 應用部分引自 [@kenwheeler](https://twitter.com/ken_wheeler) 爲這篇文章 [Create a Shopping Cart Using React.js and Flux](https://scotch.io/tutorials/creating-a-simple-shopping-cart-with-react-js-and-flux) 所作的 demo。我將其用作一個簡易的 Flux 模範，不過此項目聚焦於 Webpack 工作流。你可以當它是一個種子工程，在其基礎上建立你自己的 Flux 應用。

此模範目前爲止有以下特色：

* 遷徙至最新的 React v0.14，包括分離的 ReactDOM 包及其他新增或削除特性。請移步 [v0.14](https://facebook.github.io/react/blog/2015/10/07/react-v0.14.html) 的升級嚮導。
* **Webpack** 綑綁器。
* **Babel** 而非 JSXTransformer。
* **Webpack-dev-server** 進行熱伺服。
* **React-hot-loader** 實時重載。
* **Uglify** 綑綁後腳本。
* **Sass** 預處理樣式。所需的資源（諸如圖像和字型文件）一併綑綁入 JavaScript 中。*注意我使用 .woff 字型格式並將其轉譯爲 inline base64 string。*

## 安裝

1. 確保你的機器全局安裝了 npm 或甚或 Webpack。
2. 下載 [zip](https://github.com/jasonlam0619/flux-webpack-boilerplate/archive/master.zip) 或 `git clone git@github.com:jasonlam0619/flux-webpack-boilerplate.git` 進你的電腦。
3. `cd flux-webpack-boilerplate-master`
4. `npm install`
5. `npm start` 用 Webpack 構建綑綁包並伺服應用。
6. 造訪 `localhost: 8080`。

## 展望

日後可能會有以下升級：

* 遷徙至 ES2015 (ES6).
* Webpack 的`file-loader`加載器。