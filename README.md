# vue-calc
fix 1.1 - 1.3 = -0.19999999999999996

<a href="https://npmcharts.com/compare/vue-calc?minimal=true"><img src="https://img.shields.io/npm/dm/vue-calc.svg" alt="Downloads"></a>
<a href="https://www.npmjs.com/package/vue-calc"><img src="https://img.shields.io/npm/v/vue-calc.svg" alt="Version"></a>
<a href="https://www.npmjs.com/package/vue-calc"><img src="https://img.shields.io/npm/l/vue-calc.svg" alt="License"></a>

## Install

```
npm install vue-calc
```

## Usage

```JavaScript
import calc from 'vue-calc'
Vue.use(calc)
```

```vue.js
{{ $calc(1.1).add(-1.3) }}
```

```JavaScript
this.$calc(1.1).add(-1.3)
```

## Prototype
- $calc(x).add(y)
- $calc(x).subtract(y)
- $calc(x).multiply(y)
- $calc(x).divide(y)
