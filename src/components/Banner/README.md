## Introduce
横幅组件用于展示最新上架或广告等横幅形式的内容。

## Usage
```
<template>
  <div>
    <banner>
      <div slot="item" class="item"><img src="http://olislpb6q.bkt.clouddn.com/bizhi1.jpg"></div>
      <div slot="item" class="item"><img src="http://olislpb6q.bkt.clouddn.com/bizhi2.jpg"></div>
      <div slot="item" class="item"><img src="http://olislpb6q.bkt.clouddn.com/bizhi4.jpg"></div>
    </banner>
  </div>
</template>
<script>
import { Banner } from 'lvshou-vcomponents';
export default {
  ...
  components: { Banner },
  ...
};
</script>
```
具体使用可参考[该文件](../../examples/banner.vue)。

## Options
配置项 | 值类型 | 描述
--- | --- | ---
showPoint | Boolean | 规定是否显示底部小园点，默认`true`
`<slot name="item"></slot>` | HTML | `item`具名插槽规定子元素内容