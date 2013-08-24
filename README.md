# [ty.css](http://yukir.net/ty.css/)

***

试图提供简单易用的排版。

**它干的什么活：**

* 垂直间距
* 字号

没了。

**它不干什么活：**

* css reset
* 字体
* 格栅系统
* ruby
* 竖排

请自行搭配你惯用的框架。

**它怎么的干活：**

1. 在 `article` 或其它正文的亲元素添加 `.ty-cjk` 的 class
2. `<link rel="stylesheet" href="ty.css" media="screen" type="text/css">`
3. 如果列表项（`li`）较长，建议使用 `.ty-cjk-blocklist` 包装 `ol` 或 `ul` 元素。嗯英文这块我回头补上。

**授权**

见 LICENSE.md。
