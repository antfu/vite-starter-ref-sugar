# vite-starter-ref-sugar

![Nightly Build](https://github.com/knightlyjs/knightly/blob/main/res/badge.svg?raw=true)

[Vite](https://github.com/vitejs/vite) starter template for the [new `<script setup>` and ref sugar RFC](https://github.com/vuejs/rfcs/pull/222). Powered by [Knightly](https://github.com/knightlyjs/knightly)

> ⚠️ Please note the feature is currently still in **pending RFC** phrase which means nothing has set in stone yet. This starter template is just for experimenting purposes.


```html
<script setup>
import { computed } from 'vue'

ref: count = 0
ref: doubled = computed(() => count * 2)

const inc = () => count++
</script>
```
