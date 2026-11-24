# JavaScript 是什么
是一种运行在客户端（浏览器）的编程语言，实现人机交互效果
作用：
	+ 网页特效
	+ 表单验证(合法性判断)
	+ 数据交换（获取后端数据）
	+ 服务端编程（node.js）
有什么：
	+ ECMAScript
		  基础语法知识
	+ Web APIs
		+ DOM 页面文档对象模型
		+ BOM 浏览器对象模型

# javascript 书写位置
## 内部 js
直接写在 html 文件里，用 script 标签包住。
规范：script 标签写在</body> 上面
将</script>放在 html 文件的底部附近的原因是浏览器会按照代码在文件中的顺序加载 HTML；如果先加载的 JavaScript 期望修改 其下方的 HTML,可能由于 HTML 尚未被加载而失效。
## 外部 js
代码写在以 js 文件内
语法：通过 script 标签，引入到 html 页面中
<script src = 'my.js'></script>
注意此时，script 标签中间写的代码会被忽略
alert('')，页面弹出警告对话框
# 内联 js
代码写在标签内部
语法：vue 框架会用到这种模式
# 注释
## 单行注释
符号： //
作用是：//右边这一行的代码会被忽略
## 块注释
符号：/* \*/ 
作用是在/\*和\*/之间的所有内容都会被忽略
# 结束符
符号：(;)
作用：代表语句结束，js 中的结束符不被强制要求书写，但在实际开发中，要么每句都写，要么每句都不写




[JavaScript 指南 - JavaScript | MDN](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide...)
