了解web的架构，大致分为3个部分（客户端，服务器，大数据），其中客户端分为PC端浏览器，移动浏览器，原生应用，其他终端等。PC端浏览器和移动浏览器仍然是主流，但其他智能终端在逐渐发展。服务器端大致分为4各部分（javaEE，php，Node.js，python）其中Node.js和Python正在逐渐取代其他两种语言，但是他们之间又各有不同，谁成为主流还不清楚。大数据主要分为关系型数据库和非关系型数据库。
HTML结构主要分为4各部分（HTML声明，HTML页面的根标签，HTML头部，HTML主体）。其中HTML头部重要的标签有元标签，远标签标示HTML页面的编码格式如下
<meta charset="UTF-8">
还包括HTML页面的标题格式如下
 <title>text</title>
HTML头部<head>里面允许出现的标签为：
<style></style>——定义css代码 
<link>——引入css文件
<script></script>——定义或引入JavaScript
<meta>——定义书写格式等
<title>——定义网页标签
HTML主体<body>里面的内容则是在浏览器中显示的内容，其中里面含有两种标签：闭合标签（有开始和结束）和空标签（只有开始）。
主体中的属性：标准属性——所有标签都具备，且必须定义在开始标签
属性名=属性值
属性名 - HTML标签预定义的
属性值 - 由双引号进行包裹的
Id——唯一
Name——可以重复
Style——定义css
Class——为类，可以重复
注释：注释会被浏览器忽略，用途于解释这段代码的意思
标题元素：h1-h6其中h1搜索权限最高，其余依次递增，h1不唯一，但是最好只写一个。常用为h1-h3.
段落元素：<p>每个代表一个段落显示于浏览器
有序列表：<ol> <li>内容</li> </ol>私有属性递增其中type可以更改其排列方式，start可以更开启排列起点，但注意start只能填写数字。
无序列表：<ul> <li>内容</li> </ul>私有属性，无序排列其中type可更改其排列方式。
定义列表：<dl> <dt></dt> <dd></dd> </dl>其中<dt>类似于总的大类<dd>类似于其中小项注意区分。
列表嵌套：<ol> <li>内<ol> <li>内容</li> </ol>容</li> </ol>大致结构为这样。每套皆可重新定义type和start，但注意应不超过三层。
链接元素：<a>作用为跳转到指定HTML页面，其中herf=“地址”来定义地址，target来定义打开方式。
Target属性值有：
_self ——默认值，表示在当前窗口或页签打开
_blank ——表示在新的窗口或页签打开
_parent ——表示在父级窗口打开
_top ——表示在顶级窗口打开
 链接元素的地址类型分为两种绝对路径和相对路径
绝对地址：一旦确认不能更改。列E:\text\9.26 和www.baidu.com
相对路径：相对于你的HTML当前页面的位置来写路径其中(../——表示返回上一级)，相对路径使用较多。

其中今天学习的快捷键：
标签名+TAB ——直接显示标签
Ctrl+Shift+L ——整理格式
Ctrl+？——直接出现注释，
Alt+鼠标左键——同时多行输入

为搜索引擎定义关键词:
<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">
为网页定义描述内容:
<meta name="description" content="Free Web tutorials on HTML and CSS">
定义网页作者:
<meta name="author" content="King">
每30秒中刷新当前:
<meta http-equiv="refresh" content="30"> 
