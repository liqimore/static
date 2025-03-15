---
title: Javascript笔记（六）–History 对象 [重点]
published: 2016-04-12 21:14:27
updated: 2016-04-12 21:14:27
tags: [Default]
categories:  []
---

History 对象

history对象记录了用户曾经浏览过的页面(URL)，并可以实现浏览器前进与后退相似导航的功能。

注意:从窗口被打开的那一刻开始记录，每个浏览器窗口、每个标签页乃至每个框架，都有自己的history对象与特定的window对象关联。

语法：

window.history.[属性|方法]

注意：window可以省略。

History 对象属性

History 对象方法

使用length属性，当前窗口的浏览历史总长度，代码如下：

1

返回前一个浏览的页面

back()方法，加载 history 列表中的前一个 URL。

语法：

window.history.back();

比如，返回前一个浏览的页面，代码如下：

window.history.back();

注意：等同于点击浏览器的倒退按钮。

back()相当于go(-1),代码如下:

window.history.go(-1);