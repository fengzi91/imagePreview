# ImagePreview

一个附带简单动画效果的图片预览组件

- [Demo / 在线演示](https://fengzi91.github.io/imagePreview/examples/basic/dist/)

### 使用
- Use npm
```
npm install image-preview-simple
```
```
import imagePreview from 'image-preview-simple'
// Add on click event
imagePreview().initPreview(dom, items)
```
- use cdn
```
<script src="//cdn.jsdelivr.net/gh/fengzi91/imagepreview@main/dist/image_preview.js"></script>
```
```javascript
// add on click event
imagePreview().initPreview(dom, items)
```
### 示例文件
 - [基础用法](examples/basic/index.html)
 - [Vue](examples/vue/App.vue)
 
|参数|必填|默认值|说明|
|----|----|----|----|
|dom|是|当前要显示的图片所在 Dom|该元素必须包含 data-id (唯一 id)、data-src (或 src，图像地址)、data-width (图像宽度)、data-height (图片高度) 四个属性|
|items|否|空|不填自动获取同级包含 data-width 的元素为一组图片 <br /> false 单图模式 <br /> Dom 数组 (一组图片)|

### License
------------
MIT
