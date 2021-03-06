# A-Byte-of-Markdown
A Byte of Markdown ( Markdown简明教程)

教程地址：[http://www.yulongjun.com/A-Byte-of-Markdown](http://www.yulongjun.com/A-Byte-of-Markdown)

#Markdown是什么？
Markdown是web上的一种格式文本。Markdown功能强大，我们可以使用Markdown控制文档的显示、把文字格式为粗体或斜体、添加图像、创建列表等等。特别值得一提的是，Markdown编写只需普通文字与一些非字母字符，比如`#`或`*`，易于学习与掌握。 

Markdown文件的后缀是`.md`或`.markdown`

此篇教程就是用Markdown编写的。

#Markdown语法讲解

##1. 文本加粗、斜体和超链接
####`代码`：
```
用Markdown让词句有**加粗**或*斜体*的效果很容易.
你也可以创建一个文本超链接，像这样：[连接到Github](https://github.com)

```
####`代码的效果`：
用Markdown让词句有**加粗**或*斜体*的效果很容易.
你也可以创建一个文本超链接，像这样：[连接到Github](https://github.com)

##2. 列表
####`代码`：
```
有时候你想要带数字编号的列表

1. 一
2. 二
3. 三


有时候你想要`·`作为编号，以下3个符号`*`、`+`、`-`可以混用


* 可以用`*`
* 继续用`*`
+ 可以用`+`
+ 继续用`+`
- 可以用`-`
- 继续用`-`

还可以用分级形式


1. 第一章
2. 第二章
3. 第三章
  - 你好
  - 再见

  ```
####`代码的效果`：
有时候你想要带数字编号的列表

1. 一
2. 二
3. 三


有时候你想要`·`作为编号，以下3个符号`*`、`+`、`-`可以混用


* 可以用`*`
* 继续用`*`
+ 可以用`+`
+ 继续用`+`
- 可以用`-`
- 继续用`-`

还可以用分级形式


1. 第一章
2. 第二章
3. 第三章
  - 你好
  - 再见

##3. 图片
####`代码`：
```
Github的Yaktocat

![ Yaktocat图片](https://octodex.github.com/images/yaktocat.png)
```
####`代码的效果`：
Github的Yaktocat

![ Yaktocat图片](https://octodex.github.com/images/yaktocat.png)

##4. 标题
标题由`#`+`标题`表示，从`#`到`######`一共六个等级的标题
####`代码`：
```
#标题1
##标题2
###标题3
```
####`代码的效果`：
(为了版面美观，特此缩小3级大小)：
###标题1
####标题2
#####标题3


##5. 引用
如果你想要引用某些东西，在行前面用`>`符号。例如：
####`代码`：
```
> 我是一个小白程序员，刚开始学编程,我觉得：

>> Markdown真是一个好用的工具。

>> 编程真的是一个不停实践的过程。

> ——*于龙君*
```
####`代码的效果`：
> 我是一个小白程序员，刚开始学编程,我觉得：

>> Markdown真是一个好用的工具。

>> 编程真的是一个不停实践的过程。

> ——*于龙君*


##6. 代码加阴影和高亮
无论是一小行代码加阴影还是一整段程序加阴影，都可以用`。

####`代码`：
```
段落中出现的代码可以用，如`/usr/bin/env python3`,整个大段的程序代码也可以用：
```python
#!/usr/bin/env python3
# -*- encoding: utf-8 -*-
print('Hello,World!')
print('Hello,Markdown')
此处应该有“```”,但是整个页面格式会乱，就省略了，其实是前后都有三个“`”
```
####`代码的效果`：
段落中出现的代码可以用，如`/usr/bin/env python3`,整个大段的程序代码也可以用：
```python
#!/usr/bin/env python3
# -*- encoding: utf-8 -*-
print('Hello,World!')
print('Hello,Markdown')
```


##7. 任务列表

####`代码`：
```
我是一个程序员小白，我在学编程，我的学习列表是：
- [x] Markdown使用方法
- [x] Python3.4.x编程
- [x] Git使用方法
- [ ] Github使用方法
- [ ] shell编程
```
####`代码的效果`：
我是一个程序员小白，我在学编程，我的学习列表是：
- [x] Markdown使用方法
- [x] Python3.4.x编程
- [x] Git使用方法
- [ ] Github使用方法
- [ ] shell编程

##8. 表格
表格支持左对齐`:----`，右对齐`----:`，居中对齐 `:--:`，如果没有`:`，默认左对齐
####`代码`：
```
| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |
```
####`代码的效果`：

| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |

##9. 注脚
####`代码`：
```
这里是[^1]，这里是另一个注脚[^demo]

[^1]: 这里是注脚1。

[^demo]: 第二个注脚。 
```
####`代码的效果`：
（github不支持multimarkdown语法，这个注脚在很多软件都可以实现）
##8. emoji表情 

####`代码`：
```
我喜欢吃 :apple: ,我女朋友喜欢吃 :banana:。
```
####`代码的效果`：
我喜欢吃 :apple: ,我女朋友喜欢吃 :banana:。


#结束语
希望大家帮忙修订下文档，指正错误和格式错误的地方，不胜感激！
