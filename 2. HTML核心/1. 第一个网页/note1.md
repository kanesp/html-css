# 第一个网页
Emmet插件： 自动生成html代码片段
## 注释
注释为代码阅读者提供帮助
书写格式：
```html
<!--超链接-->
```

## 元素

```html
<a href="www.lieon.online" title="">www.google.com</a>
<title>Document</title>
```

整体称为元素： element

元素 = 起始标记(begin tag) + 结束标记(end tag) + 元素内容 + 元素属性

属性 = 属性名 +属性值

属性分类：
- 局部属性： 某些元素特有属性
- 全局属性： 所有元素通用 (title属性 and other)


```html
<meta charset="UTF-8">
```
有些元素没有结束标记，这样的元素叫做 **空元素** (meta, and img)

空元素写法：
1. ```<meta charset="UTF-8">```
2. ```<meta charset="UTF-8" />```






## 元素嵌套
元素不可以相互嵌套

父元素、子元素、祖先元素、后代元素、兄弟元素（拥有同一个父元素的两个元素）

## 标准的文档结构
HTML：页面、html文档

```html
<!DOCTYPE html>
```
文档声明，告诉浏览器，当前文档使用的html标准是html5


```html
<html lang="en">
</html>
```
根元素， 一个页面最多只能有一个，并且该元素为所有其他元素的根元素或者父元素
html5中可以不写
lang属性是一个全局属性，表示此元素内部使用的文字是哪一种自然语言书写的。


```html
<head></head>
```
文档头， 文档头内部的内容，不会显示到页面上

```html
<meta>
```
文档的元数据：附加信息
chartset:指定网页内容编码
计算机中，低压电（0-2v)0， 高压电（2-5v）1

```html
    <title>Google</title>
```
网页标题


```html
<body></body>
```
文档体，页面上所有要惨雨现实的元素，都应该放置到文档体中。
