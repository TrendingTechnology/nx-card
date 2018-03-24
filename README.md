# nx-card

<a href="https://www.npmjs.com/package/v-tooltip"><img src="https://img.shields.io/npm/v/v-tooltip.svg"/>  <img src="https://img.shields.io/npm/dm/nx-card.svg"/>  <img src="https://img.shields.io/badge/vue-2.x-brightgreen.svg" alt="vue2"></a>

!['screenshot'](https://github.com/nazar-xda/nx-card/raw/master/card.png)

Simple and beautiful card made for vue.js.

## Table of contents

- [Installation](#installation)
- [Usage](#usage)

# Installation

```
npm install --save nx-card
```

## Default import

Install all the components:

```javascript
import Vue from 'vue'
import NxCard from 'nx-card'

Vue.use(NxCard)
```

**⚠️ A css file is included when importing the package. You may have to setup your bundler to embed the css in your page.**

## Distribution import

Install all the components:

```javascript
import 'nx-card/dist/nx-card.css'
import NxCard from 'nx-card/dist/nx-card.common'

Vue.use(NxCard)
```

**⚠️ You may have to setup your bundler to embed the css file in your page.**

## Browser

```html
<link rel="stylesheet" href="nx-card/dist/nx-card.css"/>
<script src="vue.js"></script>
<script src="nx-card/dist/nx-card.browser.js"></script>
```

The plugin should be auto-installed. If not, you can install it manually with the instructions below.

Install all the components:

```javascript
Vue.use(NxCard)
```

# Usage

In the template, use the `nx-card` directive:

```vue
<nx-card	
title="Lorem ipsum dolor sit amet."
description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Commodi eveniet, iusto, exercitationem maxime sit molestias dolor mollitia quo voluptate libero optio, nihil molestiae voluptatem rem."
image="src/image.png"></nx-card>
         
```

## License

[MIT](http://opensource.org/licenses/MIT)
