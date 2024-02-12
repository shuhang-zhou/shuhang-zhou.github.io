---
export_on_save:
  html: true
---
#记录使用过程中常用的命令
以便查阅

[TOC]

##Markdown

* 顶部输入以下代码可以保存 .md 之后自动生成 .html 文件。
```md
---
export_on_save:
  html: true
---
```
* 输入 `[TOC]` 自动生成目录，但是包含标题，没办法但问题不大。
* 

## HTML

* 使用以下代码包裹需要注释的所有代码
```html
<!--
    code
-->
```

* 源代码中`<div>`元素内文本换行但不想在HTML中出现空格，可以使用注释来取消空格。
```html
<div class="content">
这里有一段文字。123<!--
-->123这里有一段文字。
</div>

```
这样两个123之间就不会有空格了。

## CSS

* 使用以下代码注释
```css
/* 占母元素整宽 */
```

* 注释使用`ctrl +/`快捷键

* margin和padding的区别：margin是外边距，padding是内边距。
