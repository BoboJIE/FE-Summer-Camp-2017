# FE-Summer-Camp-2017

翔工作室2017年夏令营前端技术培训
FE交流(答疑)群 491022835(群号)

### 准备工作(必看)

#### 1. 编辑器/IDE

推荐[Sublime Text](http://www.sublimetext.com/),[webstorm](https://www.jetbrains.com/webstorm/)
- Sublime Text是编辑器,而webstorm是IDE。
- 相对说来,Sublime Text更加轻巧,启动速度更快。但是ST需要自己安装一些插件,才能成为你的利器,不然和记事本没有多大区别。
- 作者本人更推荐使用webstorm，虽然稍微笨重(相对而言),但免去了折腾,重要的是真的很好用
- 总结一些,**如果不想折腾,请安装webstorm,如果喜欢折腾,可以两个都下载,然后选择自己喜欢的**

**如果你使用的是Sublime Text，需要自己提前装一些插件,以下我给出一些链接,作为参考**
- [Sublime Text 3常用插件安装（持续更新）](http://www.cnblogs.com/JSONBEAN/p/5894697.html)
- [ 实用的sublime插件集合 – sublime推荐必备插件](http://blog.csdn.net/qq350490977/article/details/71106921)
- [Sublime Text 3最好的功能、插件和设置](http://www.css88.com/archives/5858)

#### 2. Github

你需要注册一个[Github账号](https://github.com/)，这将在我们夏令营的后续课程用到

#### 3. 浏览器

WEB-FE开发,相当长的时间都是在和浏览器打交道的

推荐的两个浏览器分别是

- [Chrome](https://www.google.cn/chrome/browser/desktop/index.html)
- [firefox](http://www.firefox.com.cn/download/)

#### 4. 碎碎念

- 本次夏令营,每天的线上直播时间大概在一个小时-两个小时
- 直播期间会梳理脉络，宏观上进行讲解
- 每天会留下一些参考资料与一些小任务
- **如果每天不能看完留下的参考资料，跟着做小任务，恐怕收获不大（望周知）**
- 列出的课程安排仅作参考,大致讲解的内容是那些
- 会根据实际讲解效果，灵活调整


## 非工作室成员

### 第一天
- 讲解字符编码
  * [Unicode 和 UTF-8 有何区别？](https://www.zhihu.com/question/23374078)
  * [「带 BOM 的 UTF-8」和「无 BOM 的 UTF-8」有什么区别](https://github.com/cumtflyingstudio/FE-Summer-Camp-2017/edit/master/README.md)

- HTML(HyperText Markup Language)
    * 概念
    * h1-h6
    * p
    * style
    * 注释
    * a(链接)
         * target="_blank"
         * target="_self"
    * img
    *  hr
    * div
    * span
    *  br
    *  [表格](http://www.w3school.com.cn/html/html_tables.asp)   
    * 列表
    * 参考
      *  [菜鸟教程-HTML](http://www.runoob.com/html/html-tutorial.html)
      *  [w3school-HTML](http://www.w3school.com.cn/html/)
      *  [MDN-HTML](https://developer.mozilla.org/zh-CN/docs/Web/HTML)

- Emmet
  *  [Emmet-前端开发神器](https://segmentfault.com/a/1190000007812543)
  *  [前端开发必备！Emmet使用手册](http://www.w3cplus.com/tools/emmet-cheat-sheet.html)
  *  [Emmet:编写HTML+CSS必备的插件](http://caibaojian.com/emmet.html)

### 第二、三、四、五天

- CSS(Cascading Style Sheets)
   * 创建 
       * 内联样式 
       * 内部样式表 
       * 外部样式表      
 
   * 盒子模型
      * margin
      * border
      * padding
      * content 
      * box-sizing
         * content-box
         * border-box
         * inherit
   * 选择器
       * id元素器
       * class选取器
       * 元素选择器
       * 后代选择器
       * 伪类选择器     
   * display
     * inherit 规定应该从父元素继承 display 属性的值。
     * none 此元素不会被显示。
     * block 此元素将显示为块级元素，此元素前后会带有换行符。
     * inline 默认。此元素会被显示为内联元素，元素前后没有换行符。
     * inline-block 行内块元素。（CSS2.1 新增的值）   
   * position
     * inherit 规定应该从父元素继承 position 属性的值。
     * static  默认值。没有定位，元素出现在正常的流中（忽略 top, bottom, left, right 或者 z-index 声明）。
     * relative 生成相对定位的元素，相对于其正常位置进行定位。
     * fixed 生成绝对定位的元素，相对于浏览器窗口进行定位。
     * absolute 生成绝对定位的元素，相对于 static 定位以外的第一个父元素进行定位。
     
   * color
   * width
   * height
   * font-size
   * font-family
   * li
   * 链接
   * text-align
   * text-indent
   * [菜鸟教程-CSS](http://www.runoob.com/css/css-tutorial.html)
   * [w3school-CSS](http://www.w3school.com.cn/css/)
   * [MDN-CSS](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Introduction_to_CSS/How_CSS_works)
  
- CSS3部分特性
  * border-radius
  * box-shadow
  * border-image
  * Linear Gradients
  * Radial Gradients
  * text-shadow
  
  
- 响应式开发
    * viewport(ideal)
    * 媒体查询
    * [demo](http://www.sail.name/CSS_Demo/smallDemo.html)
    * [demo源码](https://github.com/iamsail/CSS_Demo/blob/master/smallDemo.html)
    ```
       <meta name="viewport"
            content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    ```
    
### 第六、七天

- JavaScript基础知识
    * DOM（Document Object Model）文档对象模型
        * 事件
        * document.getElementById(id)
        * document.getElementsByTagName(name)
        * document.createElement(name)
         * Node.appendChild(node)
         * Node.insertBefore(node)
         * element.innerHTML
         * element.innerText
         * element.style.left
         * element.setAttribute
         * element.getAttribute
         * element.addEventListener
         * JavaScript DOM编程艺术
    * BOM（Browser Object Document）即浏览器对象模型。
    * ECMAScript
         * 变量定义
         * 函数
         * 循环
         * 数组
         * Math.max() 
         * Math.min() 
          * Math.ceil() 向上舍入
          * Math.floor() 向下舍入
          * Math.round() 标准舍入
          * Math.random()  返回0和1之间的随机数，不包括0，1
         
     * 参考
         * [JavaScript 教程](http://www.w3school.com.cn/js/)
         * [DOM简介](https://www.runoob.com/js/js-htmldom.html)
         * [文档对象模型 (DOM)](https://developer.mozilla.org/zh-CN/docs/Web/API/Document_Object_Model)

### 第八、九、十天

- 实战小游戏
- 部署到Github
- 打包成APP

### 工作室成员

### 第一、二、三天
- HTML语义化
  * header
  - nav
  * footer
  - section
  * main
  * aside
  * h1-h6
  * article
  * cite
  * [一些常见html5语义化标签](http://blog.csdn.net/coco379/article/details/52938071)
  - [小知识点](http://www.sail.name/CSS_Demo/%E5%B0%8F%E7%9F%A5%E8%AF%86%E7%82%B9.html) 
 

- 布局
  * 清除浮动
      * 标签法
      * 伪元素:after
      * 设置overflow
      * 父元素同步float
      * 结合BFC灵活处理

   * BFC(Block formatting context)
     - 创建BFC
       * float属性不为none
       * position为absolute或fixed
       * display为inline-block, table-cell, table-caption, flex, inline-flex
       * overflow不为visible
       
      - 布局规则
        * 内部的Box会在垂直方向，一个接一个地放置。
        * Box垂直方向的距离由margin决定。属于同一个BFC的两个相邻Box的margin会发生重叠
        * 每个元素的margin box的左边， 与包含块border box的左边相接触(对于从左往右的格式化，否则相反)。即使存在浮动也是如此。
        * BFC的区域不会与float box重叠。
        * BFC就是页面上的一个隔离的独立容器，容器里面的子元素不会影响到外面的元素。反之也如此。
        * 计算BFC的高度时，浮动元素也参与计算  
        
    * 垂直居中
        * 单行文本垂直居中
        * 多行文本垂直居中
        * div(块级元素)垂直居中
       
    * 圣杯布局
    * 双飞翼布局

- flex布局
  * 容器属性
    - flex-direction
    - flex-wrap
    - flex-flow
    - justify-content
    - align-content  
    - align-items
  * 项目属性
    - flex-grow
    - flex-shrink
    - flex-basis
    - flex
    - order
    - align-self
  
  * 参考
    
    - [Flex基础](http://www.sail.name/2017/07/09/the-base-of-flex/)
 
- 一些CSS技巧

### 第四、五天

- 讲解CSS动画
  * transform
     * rotate 旋转元素
     * scale 缩放元素
     * translate 移动元素
     * skew 倾斜元素
     * perspective 透视
  
   * transition
      * transition-property  过渡的CSS属性
      * transition-duration   过渡时间 
      * transition-delay      延迟时间
      * transition-timing-function  过渡动画的效果
         * ease：缓解效果，等同于cubic-bezier(0.25,0.1,0.25,1.0)函数，既立方贝塞尔。
         * linear：线性效果，等同于cubic-bezier(0.0,0.0,1.0,1.0)函数。
         * ease-in：渐显效果，等同于cubic-bezier(0.42,0,1.0,1.0)函数。
         * ease-out：渐隐效果，等同于cubic-bezier(0,0,0.58,1.0)函数。
         * ease-in-out：渐显渐隐效果，等同于cubic-bezier(0.42,0,0.58,1.0)函数。
         * cubic-bezier：特殊的立方贝塞尔曲线效果。
     
  * animation
      * animation-name  动画名称
      * animation-duration  动画时间
      * animation-iteration-count 对象动画循环播放的次数。
      * animation-timing-function  播放方式
         * ease：缓解效果，等同于cubic-bezier(0.25,0.1,0.25,1.0)函数，既立方贝塞尔。
         * linear：线性效果，等同于cubic-bezier(0.0,0.0,1.0,1.0)函数。
         * ease-in：渐显效果，等同于cubic-bezier(0.42,0,1.0,1.0)函数。
         * ease-out：渐隐效果，等同于cubic-bezier(0,0,0.58,1.0)函数。
         
  * transform-style
      * 3D呈现
      * flat | preserve-3d
      * flat：所有子元素在 2D 平面呈现
      * preserve-3d：保留3D空间
       
   * [demo](http://www.sail.name/CSS_Demo/rotary-cube.html)
   * [demo源码](https://github.com/iamsail/CSS_Demo/blob/master/rotary-cube.html)
  
- 结合CSS预处理器(LESS/SASS/STYLUS)高效开发
  * 环境准备 
      * [Node.js](https://nodejs.org/en/#download)
  * 安装
      * npm install stylus
      * npm install stylus -g
   * 编译
       * stylus xxx.styl
       * stylus --compress xxx.styl
       * stylus -w style.styl -o style.css
       
  * stylus
     * 选择器
     * 变量 
     * 插值
     * 方法/函数
     * 注释
        * 单行注释,双斜杠,CSS中不输出
        * 多行注释,它们只有在compress选项未启用的时候才会被输出
        * 多行缓冲注释,Stylus压缩的时候这段无视直接输出
     * 迭代 
     * 关键帧(@keyframes)
     * CSS字面量(CSS Literal)
 
  * [stylus-github](https://github.com/stylus/stylus)
  * [stylus中文版参考文档之综述](http://www.zhangxinxu.com/jq/stylus/) 
      
### 第六、七天

 - 执行环境
    * 定义了变量或函数有权访问的其它数据,决定了他们各自的行为
 - 作用域链(scope chain)
    * 保证对执行环境有权访问的所有变量和函数的有序访问
- JS闭包(closure)
     * 闭包是指有权访问另一个函数作用域中变量的函数
     * 创建闭包的最常见的方式就是在一个函数内创建另一个函数，通过另一个函数访问这个函数的局部变量,利用闭包可以突破作用链域
   
     * 特性/作用
          * 函数内再嵌套函数
          * 参数和变量不会被垃圾回收机制回收
          * 读取函数内部的变量
- 面向对象
- 设计模式
- 部分ES6
    * let
    * const
    * 模板字符串
    * 函数默认参数
    * Array.of()
    * Array.fill()
   
### 第八、九、十天

- 将CSS动画与websocket结合,调用API,通过移动端控制PC端动画
