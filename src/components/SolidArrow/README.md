## Introduce
实心箭头组件用于绘制页面中实心的小箭头。

## Usage
```
<template>
  <div>
    <solid-arrow
      @click.native="active2 = !active2"
      :active="active2"
      :top="'390px@380px'"
      :left="'90px@70px'"
      :direction="'left'"
      :color="'#ea64ff@#ff607c'"
      :size="'12px@24px'"
      >
    </solid-arrow>
  </div>
</template>
<script>
import { SolidArrow } from 'lvshou-vcomponents';
export default {
  ...
  components: {
    SolidArrow
  },
  ...
};
</script>
```
具体使用可参考[该文件](../../examples/arrows.vue)。

## Options
配置项 | 值类型 | 描述
--- | --- | ---
size | String | 规定箭头大小，默认`8px`
color | String | 规定箭头颜色，默认`#666`
direction | `left` `top` `right` `bottom` | 规定箭头指向，默认`right`
active | Boolean | 规定箭头组件是否处于激活状态，若处于激活状态，会渲染`@`后的样式（若`@`后没有内容，则不改变样式），默认`false`