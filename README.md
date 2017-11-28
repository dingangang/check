# [Bulma](https://bulma.io)

Bulma 是一个基于 [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes) 的**先进CSS 框架** 

本文中主要是进行了翻译，方便模块的查看。并且准备构建一些DEMO方便对照查看使用。
<a href="https://bulma.io"><img src="https://raw.githubusercontent.com/jgthms/bulma/master/docs/images/bulma-banner.png" alt="Bulma: a Flexbox CSS framework" style="max-width:100%;" width="600" height="315"></a>

## Quick install

Bulma现在正在持续的开发中，通过以下方式可以快速部署

### NPM

```sh
npm install bulma
```
**or**

### Yarn

```sh
yarn add bulma
```

### Bower

```sh
bower install bulma
```

### CDN

```sh
https://cdnjs.cloudflare.com/ajax/libs/bulma/0.6.0/css/bulma.min.css
https://cdnjs.cloudflare.com/ajax/libs/bulma/0.6.0/css/bulma.css.map
```

[https://cdnjs.com/libraries/bulma](https://cdnjs.com/libraries/bulma)

上方网站是完整的CDN，也可以在该站提供意见和需求.

## CSS only

Bulma是**纯CSS**框架。因此，最后的输出只有一个单个的CSS文件： [bulma.css](https://github.com/jgthms/bulma/blob/master/css/bulma.css)

您可以直接使用该文件，也可以下载SASS源代码来定制变量 [variables](https://bulma.io/documentation/overview/variables/).

项目中**没有JavaScript**。通常人们喜欢同自己的JavaScript来实现功能。Bulma可以视为"environment agnostic"（环境不可知论者），即是Bulma可以在不同的项目环境中使用。Bulma只关注样式层的实现而不不包括逻辑层。

## 浏览器支持

Bulma 采用了 [autoprefixer](https://github.com/postcss/autoprefixer)来解决一些早期的浏览器版本关于Flexbox特性的兼容性问题。通过[Can I use](https://caniuse.com/#feat=flexbox)，Bulma兼容以下浏览器的**近期版本**

* Chrome
* Edge
* Firefox
* Opera
* Safari

Internet Explorer （10+）只支持了部分支持。

## 文档

The documentation resides in the [docs](docs) directory, and is built with the Ruby-based [Jekyll](https://jekyllrb.com/) tool.

Browse the [online documentation here.](https://bulma.io/documentation/overview/start/)

## 相关的项目

| Project                                                                            | Description                                                        |
|------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| [Bulma with Attribute Modules](https://github.com/j5bot/bulma-attribute-selectors) | Adds support for attribute-based selectors.                        |
| [Bulma with Rails](https://github.com/joshuajansen/bulma-rails)                    | Integrates Bulma with the rails asset pipeline                     |
| [Vue Admin](https://github.com/vue-bulma/vue-admin)                                | Vue Admin framework powered by Bulma                               |
| [Bulmaswatch](https://github.com/jenil/bulmaswatch)                                | Free themes for Bulma                                              |
| [Goldfish](https://github.com/Caiyeon/goldfish)                                    | Vault UI with Bulma, Golang, and Vue Admin                         |
| [ember-bulma](https://github.com/open-tux/ember-bulma)                             | Ember addon providing a collection of UI components for Bulma      |
| [Bloomer](https://bloomer.js.org)                                                  | A set of React components for Bulma                                |
| [Re-bulma](https://github.com/bokuweb/re-bulma)                                    | Bulma components build with React                                  |
| [React-bulma](https://github.com/kulakowka/react-bulma)                            | React.js components for Bulma                                      |
| [Buefy](https://buefy.github.io)                                                   | Lightweight UI components for Vue.js based on Bulma                |
| [vue-bulma-components](https://github.com/vouill/vue-bulma-components)             | Bulma components for Vue.js with straightforward syntax            |
| [BulmaJS](https://github.com/VizuaaLOG/BulmaJS)                                    | Javascript integration for Bulma. Written in ES6 with a data-* API |
| [Bulma.styl](https://github.com/log1x/bulma.styl)                                  | 1:1 Stylus translation of Bulma                                    |
| [elm-bulma-classes](https://github.com/danielnarey/elm-bulma-classes)              | Bulma prepared for usage with ELM                                  |
| [Bulma Customizer](https://bulma-customizer.bstash.io/)                            | Bulma Customizer &#8211; Create your own **bespoke** Bulma build   |
| [Fulma](https://mangelmaxime.github.io/Fulma/)                                     | Wrapper around Bulma for [fable-react](https://github.com/fable-compiler/fable-react)   |
| [Laravel Enso](https://github.com/laravel-enso/enso)                               | SPA Admin Panel built with Bulma, VueJS and Laravel 			      |
| [Django Bulma](https://github.com/timonweb/django-bulma)                           | Integrates Bulma with Django 			    |

## Copyright and license

Code copyright 2017 Jeremy Thomas. Code released under [the MIT license](https://github.com/jgthms/bulma/blob/master/LICENSE).
