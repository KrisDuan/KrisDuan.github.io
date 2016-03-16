#task1-1总结：
>[task1-1要求](http://ife.baidu.com/task/detail?taskId=1)
>[mytask代码](https://github.com/KrisDuan/2016-ife-mytask/tree/master/task1) 详见task1-1-1
>[demo展示](http://krisduan.github.io/task1-1-1.html)

- 空格:`&nbsp;`主要用于多次空格时使用； 版权符号&copy;：`&copy;` 
- 段落或区块缩进可以使用`<blockquote>`也可以使用自定义列表`<dl>`

![整块缩进](http://upload-images.jianshu.io/upload_images/176220-5e63bca6a2d4a88b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 无内容元素（Void elements）：无内容元素是一种不能包含任何内容的特殊元素。
  - 比较常见的无内容元素有：`<br>` `<hr>` `<img>` `<input>` `<link>` `<meta>`
  - 倒数第二部分的 “/” 字符是可选的，而且没有任何实际含义。所以 `<br>`和`<br />`其实没有实质区别。

#task1-2总结：
>[task1-2要求](http://ife.baidu.com/task/detail?taskId=2)
>[mytask代码](https://github.com/KrisDuan/2016-ife-mytask/tree/master/task1) 详见task1-2-1
>[demo展示](http://krisduan.github.io/task1-2-1.html)

- 在制作导航条的时候，目的将每一个`<li>`横向排列，在css中使用`li{display:inline;}`之后发现列表前面的圆点会消失，作业要求要保留圆点，参考其他同学的代码，找到了一种更好的方法使列表横线排列而且保留圆点符号：使用浮动`li{float:left/right;}`，有效的解决了问题。

![浮动后的列表导航选项](http://upload-images.jianshu.io/upload_images/176220-f2a29e2a71c73a13.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 伪类的使用
 `a.red : visited {color: #FF0000}`
`<a class="red" href="css_syntax.asp">CSS Syntax</a>`
- 消除单元格之间的间距`table{border-collapse:collapse}`
- 设置边框弧度`****{border-radius: 15px;}`
- 完成task时这个样式不会写，参考同学代码，才发现原来是单独一侧的边框加上相应的样式，我开始以为是类似markdown中块引用语法。

![border-left: 3px solid #BBBBBB;](http://upload-images.jianshu.io/upload_images/176220-54bd54a90f49d9eb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 如下样式起初不会写，左侧、右侧都要靠近中间这条空隙，感觉很难办到。参考同学代码发现他们使用的样式有点高深，作为初学者的我看不懂。经过思考，最终想到了之前学习布局时使用的“表格布局”，我把它看作9行2列的列表，第一列单元格右对齐，第二列单元格左对齐，第一列最后一个元素还要使用垂直向上对齐。`<td align="right" valign="top">个人描述：</td>`，在加上一些css样式，使边框透明等，就达到了task要求的效果

![表格妙用](http://upload-images.jianshu.io/upload_images/176220-80bb8c812ce795fa.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


