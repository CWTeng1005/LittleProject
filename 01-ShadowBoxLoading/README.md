## ShadowBoxLoading

### 代码解释  
- index.html 中的 div class="loader" 包含7个 span 元素，每个 soan 作为一个加载条块  
- style.css 中，body 样式设置页面背景图片，loader 的 display: flex 水平布局加载条块  
- 每个 span 元素使用 animation-delay 设置不同的动画延迟，形成加载动画的顺序  
- @keyframes animate 动画定义了加载条的移动、放大和阴影效果的变化，形成闪动和移动效果  