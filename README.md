# vue-xripple
ripple effect for google material design

## Source
this code from [Vuetify](https://vuetifyjs.com)

## Install
### npm
```shell
npm install vue-xripple
```
### yarn
```shell
yarn add vue-xripple
```

## Usage
In `main.js`

```javascript
import xripple from 'vue-xripple';
import Vue from 'vue';

Vue.use(xripple);

```

In vue component

```vue
<template>
  <div>
    <button v-ripple>click me</button>
  </div>
</template>
```

## License
MIT