# vue-calc

[![Greenkeeper badge](https://badges.greenkeeper.io/chiaweilee/vue-calc.svg)](https://greenkeeper.io/)

fix 1.1 - 1.3 = -0.19999999999999996

# Install

```
npm install vue-calc
```

# Usage

```vuejs
import calc from 'vue-calc'
Vue.use(calc)
```

```vue
<template>
{{ $calc(1.1).add(-1.3) }}
</template>
```

# Support
- $calc(x).add(y)
- $calc(x).subtract(y)
- $calc(x).multiply(y)
- $calc(x).divide(y)
