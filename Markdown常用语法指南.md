# MarkDown常用语法指南

本文记录了在使用编辑器 *MarkdownPad2* 过程中常用到的语法。如有错误，还望指正。

---

## 目录
1. [分级标题 ](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#1分级标题) 
2. [列表](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#2列表)  
	 2.1 [无序列表](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#12无序列表)  
	 2.2 [有序列表](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#12无序列表)
3. [斜体和粗体](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#3斜体和粗体)
4. [超链接](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#4超链接)  
     4.1 [文字超链接](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#41文字超链接)  
	 4.2 [图片链接](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#42图片链接)
5. [文字引用](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#5文字引用)
6. [代码块](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#6代码块)  
	 6.1 [行内代码 ](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E5%B8%B8%E7%94%A8%E8%AF%AD%E6%B3%95%E6%8C%87%E5%8D%97.md#61-行内代码)    
	 6.2 多行代码  

---
## 1.分级标题

    # 这是一级标题
	## 这是二级标题
	...
	###### 这是六级标题
对应：
# 这是一级标题
## 这是二级标题   
...   
###### 这是六级标题	
  
注：  

1. GitHub的内置浏览器规定 # 与标题文字之间有空格，但MarkDownPad中无此要求。为了养成好的习惯，最好空一个空格出来。   
1. 标题至多有六级。

## 2.列表
### 1.1无序列表
*，＋，－均可创建无序列表

	* 用 * 表示
	+ 用 + 表示
	- 用 - 表示

对应:

* 用 * 表示
+ 用 + 表示
- 用 - 表示
### 1.2有序列表

使用英文的数字和点创建有序列表（中间要加空格）

	1. 有序列表
	2. 有序列表

对应：   
  
1. 有序列表
2. 有序列表

## 3.斜体和粗体

	*斜体*  
	**粗体**

对应：
	
*斜体*  
**粗体**

## 4.超链接
### 4.1文字超链接
	[百度](www.baidu.com)

对应：

[百度](www.baidu.com)

### 4.2图片链接

	![](http://i.imgur.com/afD9lSD.jpg)

对应：

![](http://i.imgur.com/afD9lSD.jpg)

## 5.文字引用

	> 文字引用举例

对应：

> 文字引用举例

## 6.代码块 
### 6.1 行内代码  

	我们可以用`Margin`来表示外边距。

对应：

我们可以用`Margin`来表示外边距。

### 6.2 多行代码
输入多行代码，只需将代码整体缩进4个空格或者按Tab键缩进即可。

	<!DOCTYPE html>
	<head>
		<title>sayHi</title>
		<meta charset="UTF-8">
		<style>
			.container{
				width: 40px;
				height: 40px;
				background-color: red;
			}
		</style>
	</head>
	<html>
		<div id="container"><div>
	</html>
***注意：**   
如果根据上面的写法没有实现效果的话，可以尝试：
       
- 将符号与文字中间加上空格 
- 上一行后面连续按三次空格换行
- 前一行后面加空格
- 有一定的基础以后，可以看下面的[教程](https://github.com/WaltTing/Tools-For-Develop/blob/master/Markdown%E8%AF%AD%E6%B3%95%E8%BF%9B%E9%98%B6%E7%89%88.md)。



