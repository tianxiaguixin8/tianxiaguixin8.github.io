---
title: Angular2模板中设置非字符串的元素属性
date: 2016-12-21 16:15:25
tags:
- Angular2
---
html中元素的属性都为字符串，如过要在Angular2模板中设置非字符串的元素属性需要使用属性绑定方式。

`<input type="radio" name="is_used" value="1">`

改为

`<input type="radio" name="is_used" [value]="1">`



在Angular2属性绑定中使用字符串：

`<input type="radio" name="is_used" [value]="'ssss'">`