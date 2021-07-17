# 《HTML入门笔记1》
## 什么是HTML？
HTML的全称为超文本标记语言，是一种标记语言。它包括一系列标签．通过这些标签可以将网络上的文档格式统一，使分散的Internet资源连接为一个逻辑整体。HTML文本是由HTML命令组成的描述性文本，HTML命令可以说明文字，图形、动画、声音、表格、链接等。

## HTML的发明者
www = URL + HTTP + HTML，www就是万维网 world wide web，在90年代诞生，创始人是Tim Bermers-Lee ，又叫李博士。

他写了第一个浏览器，写了第一个服务器，发明了WWW，同时发明了HTML、HTTP和URL

## HTML起手

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
## 常用的表章节标签

h1~h6:标题元素标签，代表文档中不同级别的内容，有助于章节的结构化；例如：h1表示主标题。

section：对页面上的内容进行分块，或者说对文章进行分段，一般来说出现在文档的大纲中，包含标题元素标签。

article:表示文档、页面、应用或网站中的独立结构，是可独立分配或者可复用的结构。article中可包含一个或多个section。

main:呈现文档的body或应用的主体部分。

aside：呈现了文档的旁支内容，通常表现为侧边栏或者标注框，可以单独拆分而不会影响整体。


## 全局属性
class：规定元素的一个或多个类名。

contenteditable：规定元素内容是否可编辑。

id：规定元素的唯一 id。

style：规定元素的行内 CSS 样式。

title：规定有关元素的额外信息。


## 常用的内容标签以及意思

a：可以通过a的herf属性创建访问其它网页、文件、电子邮箱的超链接。

strong：表示文本很重要，加粗显示。

em：文本表示为强调的内容，一般用斜体来显示。

code：是一个短语标签，用来定义计算机代码文本。

pre:定义预格式化的文本，被包围在 pre 标签中的文本通常会保留空格和换行符，并且文本也会呈现为等宽字体。

我的联系方式：[电子邮箱](lijunll35@163.com)