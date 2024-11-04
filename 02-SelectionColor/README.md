## SelectionColor  

- body样式：
    - 通过清除 margin 和 padding 使页面更加整洁  
    - 设置 font-family 来定义全局的字体样式，优先使用 Impact 字体，没有时使用其他备选的无衬线字体  

- .container 样式：  
    - 设置容器宽度为页面宽度的70%，并通过 margin: 0 auto; 使其水平居中  

- h1::selection 和 p::selection 伪元素：  
    - ::selection 是一个CSS伪元素，用于定义文本被选中时的样式  
    - 在 h1::selection 中，设置标题被选中时的背景色和文字颜色  
    - 在 p::selection 中，设置段落被选中时的背景色和文字颜色  

> **这段文字样式的效果是当用户在页面上选择文本时，标题和段落会分别显示不同的高亮颜色**