# [ty.css](http://yukir.net/ty.css/)

---

css framework for out-of-box typography.

**what it includes:**

+ vertical spacing
  
  matches a 8px baseline system, which is half of default browser font size

+ fail-safe max width

  50 letters wide

**what it ignores:**

- global css reset
- grid system
- ruby
- vertical typography

please use with other parts.

**how to use:**

1. attach `.ty-latin`(coming soooon) to `article` or whatever encloses text
2. `<link rel="stylesheet" href="ty.css" media="screen" type="text/css">`

**license:**

see license.md

---

试图提供简单易用的排版。

**它干的什么活：**

* 垂直间距

  对齐浏览器默认字号的一半即 8px 的基线系统

* 最低限度的宽度设置

  你要是敢超过 50 字宽我就跳出屏幕削你。

没了。

**它不干什么活：**

* css reset
* 格栅系统
* ruby
* 竖排

 你以为我不想啊。

请自行搭配你惯用的框架。照说这些东西都是只管宽度的所以跟我这应该不冲突吧大概。

**它怎么的干活：**

1. 在 `article` 或其它正文的亲元素添加 `.ty-cjk` 的 class
2. `<link rel="stylesheet" href="ty.css" media="screen" type="text/css">`
3. 如果列表项（`li`）较长，建议使用 `.ty-cjk-blocklist` 包装 `ol` 或 `ul` 元素。嗯英文这块我回头补上。

**授权**

见 LICENSE.md。
