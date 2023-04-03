

# My Blog


### Markdown语法

#### 1. 标题语法

`###`后加空格代表三级标题



#### 2. 段落语法

使用空白行将文本分隔



#### 3. 换行语法

在一行的末尾添加两个空格回车



#### 4. 强调语法

**粗体** 在前后各添加**两个**星号`*`或下划线`_`

*斜体* 在前后各添加**一个**星号`*`



#### 5. 引用语法

在段落前添加一个 `>` 

> 这是引用语法
>
> 块引用嵌套在要嵌套的段落前添加一个 `>>` 
>
> > 这是嵌套



#### 6. 列表语法

有序列表在数字后加一个英文点`.`

无序列表用 `-` 、`*`或 `+`

- 破折号

* 星号

+ 加号



#### 7. 代码语法

将文本表示为`代码块`用反引号(`)包裹

代码块

使用两个（```）把代码围起来

```c
int main(){
    printf("hello");
}
```

在代码前加制表符

	代码块
在代码前加四个空格

    hello world

代码块前要有空行，Typora实时渲染模式下无法通过此方法生成代码块



#### 8. 分隔线语法

在单独一行上使用三个或多个星号 (`***`)、破折号 (`---`) 或下划线 (`___`) ，不能包含其他内容



#### 9. 链接语法

```text
这是一个链接 [Markdown语法](https://markdown.com.cn)
```

这是一个链接 [Markdown语法](https://markdown.com.cn)

给链接增加 Title

```text
这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")
```
这是一个链接 [Markdown语法](https://markdown.com.cn/ "最好的markdown教程")

网址和Email

```text
<https://markdown.com.cn>
<fake@example.com>
```

<https://markdown.com.cn>
<fake@example.com>

引用类型链接
`[hobbit-hole] [1]`

`[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`



#### 10. Markdown 图片语法

要添加图像，请使用感叹号 (`!`), 然后在方括号增加替代文本，图片链接放在圆括号里，括号里的链接后可以增加一个可选的图片标题文本。

插入图片Markdown语法代码：`![图片alt](图片链接 "图片title")`。

对应的HTML代码：`<img src="图片链接" alt="图片alt" title="图片title">`

```text
![这是图片](/assets/img/philly-magic-garden.jpg "Magic Gardens")
```


链接图片

给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中。

```text
[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)
```


#### 11. Markdown 转义字符语法

要显示原本用于格式化 Markdown 文档的字符，请在字符前面添加反斜杠字符 \ 。

```text
\* Without the backslash, this would be a bullet in an unordered list.
```
\* Without the backslash, this would be a bullet in an unordered list.



#### 12. Markdown 内嵌 HTML 标签

对于 Markdown 涵盖范围之外的标签，都可以直接在文件里面用 HTML 本身。如需使用 HTML，不需要额外标注这是 HTML 或是 Markdown，只需 HTML 标签添加到 Markdown 文本中即可。

```text
This **word** is bold. This <em>word</em> is italic.
```
This **word** is bold. This <em>word</em> is italic.




[我的GitHub主页](https://github.com/zywe)
