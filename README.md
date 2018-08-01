
# lvshou-vcomponents
hxsapp.com 前端开发尝试和积累的 vue-components,目前组件的开发有三种覆盖：
##（1）vue格式文件来组件声明方式，业务来调用引入组件声明
### ps：计划组内成员可以全部驾驭，工作在于支持业务和输出高质量的文档，难度点：★☆☆☆☆

##（2）js文件和vue格式混编的开发方式，使用全局js的函数api方式来调用组件
### ps：计划组内成员部分驾驭，使用到vue实现对象的部分方法和属性调用，涉及dom操作联动，再要输出文档，难度点：★★☆☆☆

##（3）基于jsx语法的方式的vue格式文件，来声明组件
### ps：计划组内成员部分驾驭，使用到vue属性的render方式来定义业务，去掉来template方式的声明html模版，难度点：★★★☆☆

## 最后，组件开发完毕之后，组件的跨项目调用，工程化打包后上传项目到npm上，难度点：★★★★☆


☆☆☆☆



## Installation
```
npm install lvshou-vcomponents
```

## Import
```
import 'lvshou-vcomponents/dist/lvshou-vcomponents.min.css';
import { Loading, SolidArrow... } from 'lvshou-vcomponents';
```

## Content
[SlidDelete 滑动删除组件](./src/components/SlidDelete)

[Hint 透明提示组件](./src/components/Hint)

[Loading 加载状态组件](./src/components/Loading)

[FixedTitle 表头固定组件](./src/components/FixedTitle)

[ToTop 页面置顶组件](./src/components/ToTop)

[HollowArrow 空心箭头组件](./src/components/HollowArrow)

[SolidArrow 实心箭头组件](./src/components/SolidArrow)

[Round 圆形组件](./src/components/Round)

[ProgressBar 进度条组件](./src/components/ProgressBar)

[OmitText 文本省略组件](./src/components/OmitText)

[Banner 横幅组件](./src/components/Banner)

## Demo
下载该项目，在文件根目录下依次输入命令行：
```
npm install
npm run dev
```
然后在浏览器里输入`http://localhost:8089`，即可看到组件 demo。

## Changelog
### 2018.4.21
> v0.1.6 * 添加滑动删除组件的删除按钮自定义

### 2018.4.17
> v0.1.4 * 取消圆形组件、空心和实心箭头组件的绝对定位设置

> v0.1.3 * 修改进度条组件高度设置，并去除多余样式

### 2018.3.26
> v0.1.1 * 添加横幅组件

### 2018.3.11
> v0.1.0 * 添加圆形组件、空心和实心箭头组件的激活状态

### 2018.2.28
> 创建文本省略组件

### 2018.2.26
> v0.0.29 * 删除原箭头组件，创建空心箭头和实心箭头组件

### 2018.2.9
> 创建 README.md、进度条和圆形组件

### 2018.1.14
> v0.0.27 * 创建箭头组件

### 2018.1.10
> v0.0.25 * 初始化项目，创建滑动删除、透明提示、加载状态、表头固定、页面置顶组件

## 参考工具资料
> http://www.mdeditor.com/
