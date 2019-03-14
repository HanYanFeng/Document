# Markdown
Markdown是一种轻量级标记语言，它以纯文本形式(易读、易写、易更改)编写文档，并最终以HTML格式发布。
Markdown也可以理解为将以MARKDOWN语法编写的语言转换成HTML内容的工具。

将Markdown应用于Xcode并且可以导出和苹果官方文档类似风格的文档
[点击这里](https://segmentfault.com/a/1190000005729095)

标题
#  一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

 段落
 
段落的前后要有空行，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用两个以上空格加上回车（引用中换行省略回车）。

区块引用

在段落的每行或者只在第一行使用符号>,还可使用多个嵌套引用，如：

>区块引用
>> 嵌套引用

代码区块
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如
普通段落：

    void main()
    {
       printf("Hello, Markdown.");
    }

强调

在强调内容两侧分别加上*或者_，如：

>*斜体*，_斜体_
>>**粗体**，__粗体__

列表

使用·、+、或-标记无序列表，如：

+ 第一项
- 第二项

有序列表的标记方式是将上述的符号换成数字,并辅以.，如：

1. 第一项  
2. 第二项
3. 第三项

分割线

分割线最常使用就是三个或以上*，还可以使用-和_。

___

链接
链接可以由两种形式生成：行内式和参考式。
>行内式：
>>[younghz的Markdown库](https:://github.com/younghz/Markdown "Markdown")。

>参考式：
>>
[younghz的Markdown库1][1]
[younghz的Markdown库2][2]
[1]:https://github.com/younghz/Markdown
[2]:https:://github.com/younghz/Markdown "Markdown"
注意：上述的[1]:https:://github.com/younghz/Markdown "Markdown"不出现在区块中

图片

添加图片的形式和链接相似，只需在链接的基础上前方加一个！。

![图片](https://b-ssl.duitang.com/uploads/item/201504/16/20150416H3116_MQSsF.jpeg)
![刘涛][3]
[3]:https://b-ssl.duitang.com/uploads/item/201504/16/20150416H3116_MQSsF.jpeg

反斜杠\

相当于反转义作用。使符号成为普通符号。

符号'`'

起到标记作用。如：

Chrome下的插件诸如stackedit与markdown-here等非常方便，也不用担心平台受限。
在线的dillinger.io评价也不错
Windowns下的MarkdownPad也用过，不过免费版的体验不是很好。
Mac下的Mou是国人贡献的，口碑很好。
Linux下的ReText不错。

[以上原文连接](https://github.com/younghz/Markdown)

dog | bird | cat
----|------|----
foo | foo  | foo
bar | bar  | bar
baz | baz  | baz
[其它文章连接](http://blog.leanote.com/post/freewalk/Markdown-语法手册#title-6)