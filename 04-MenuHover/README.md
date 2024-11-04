## MenuHover  

- body 样式：  
    - 清除 margin 和 padding 让页面更干净  
    - 设置字体为等宽字体，背景为 lemonchiffon  

- ul 样式：  
    - 使用 position: absolute 和 transform: translate (-50%, -50%) 使导航菜单居中  
    - display: flex 实现水平布局，使列表项在一行排列  
    - font-weight: 700 将列表项字体设置为较粗  

- ul li 样式：  
    - list-style: none 去除默认的列表项符号  
    - transition: .5s 设置过渡效果，让 li 项的样式变化更平滑  

- ul li a 样式  
    - position: relative 让链接元素为相对定位，便于后续调整  
    - text-align: center 和 display: block 将文字居中对齐  
    - text-transform: uppercase 将文字转为大写  
    - 设置较大的 dont-size: 40px 和适当的 margin 为链接项增加视觉间距  

- ul:hover li 样式：
    - 当鼠标悬停在 ul 元素上时，所有 li 项变为20%透明度并添加2像素模糊，制造一种失焦效果  

- ul li:hover 样式：  
    - 当鼠标悬停在单个 li 项时，恢复其透明度和清晰度  