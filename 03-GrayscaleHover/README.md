## GrayscaleHover  

### HTML 部分  
- img 标签用于在页面中样显示 flover.gif  
- link 标签引入外部的 style.css 文件，应用其中的 css 样式  

### CSS 部分  
- body 样式：清除页面默认的 margin 和 padding，并设置背景色  
- img 样式：通过 position: absolute 和 transform: translate (-50%, -50%) 实现图片居中  
- filter: grayscale(100%)：将图片初始显示为灰度  
- transition: 1s ease-in-out：鼠标悬停时的渐变效果  
- img: hover：当鼠标悬停在图片上时，将 filter 的灰度值改为0%，图片恢复到原始色彩  