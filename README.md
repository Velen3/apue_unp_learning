# 以下文字及格式为练手用，目的是快速熟悉Markdown格式，文档来自
[菜鸟教程](https://www.runoob.com/markdown/md-tutorial.html)
---
---
---
---
---
---
---
---
---

# Markdown教程
![Markdown](https://www.runoob.com/wp-content/uploads/2019/03/iconfinder_markdown_298823.png)

* Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
* Markdown 语言在 2004 由约翰·格鲁伯（英语：John Gruber）创建。
Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。
* Markdown 编写的文档后缀为 .md, .markdown。

---

## Markdown应用

Markdown 能被使用来撰写电子书，如：Gitbook。  
当前许多网站都广泛使用 Markdown 来撰写帮助文档或是用于论坛上发表消息。例如：GitHub、简书、reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge等。  

---

## 编辑器
本教程将使用 VSCode 编辑器来讲解 Markdown 的语法，VSCode 支持 MacOS 、Windows、Linux 平台，且包含多种主题。  
VSCode 默认认集成了 Markdown 文档编辑插件，原生就支持高亮 Markdown 的语法。  
VSCode（全称：Visual Studio Code）是一款由微软开发且跨平台的免费源代码编辑器。  
* <B>Vscode 安装教程： </B> <https://www.runoob.com/w3cnote/vscode-tutorial.html>  
* <B>Vscode 官网地址： </B> <https://code.visualstudio.com/>

![InVscode](https://www.runoob.com/wp-content/uploads/2019/03/91542A7F-900B-4C1F-9FEA-BC418A0047E5.jpeg)

VSCode 实时预览还需要执行 `Markdown: Open Preview to the Side` 命令来实现。  
在命令窗口输入 `Markdown: Open Preview to the Side` 命令：

![InVscode](https://www.runoob.com/wp-content/uploads/2019/03/35CB35BB-AC03-4A0D-9C94-AC3B24AFCB30.jpeg)

最终效果：

![InVscode](https://www.runoob.com/wp-content/uploads/2019/03/18EE1A99-AF14-4C67-85CD-A7261FD3464B.jpeg)

如果你需要将 markdown 转为 PDF、图片、HTML 等格式也可以安装对应的插件来实现。  
你也可以使用我们的在线编辑器来测试：<https://c.runoob.com/front-end/712>。

---

## 测试实例

接下来的测试中，我们先在 VSCode 下安装 <B>Markdown Preview Enhanced </B>插件来实现更强大的功能。  
点击右侧栏扩展按钮，查找<B>Markdown Preview Enhanced </B>插件，点击安装：  
![InVscode](https://www.runoob.com/wp-content/uploads/2019/03/5D9D9109-C12A-4D81-9E91-3D3FE603DFB8.jpeg)

<B>安装完成后重启 VSCode。</B>  
在 RUNOOB.md 输入以下代码：

    # RUNOOB Markdown Test
    ## Hello World!

将该代码格式粘贴到文件 RUNOOB.md 上，效果如下：
![InVscode](https://www.runoob.com/wp-content/uploads/2019/03/123F0547-C529-4D85-920F-624E65D35DD3.jpeg)
在预览框中右击鼠标还提供了各种导出功能：
![InVscode](https://www.runoob.com/wp-content/uploads/2019/03/3292631D-2230-48B5-A2B9-1E1DA1E522B7.jpeg)

---

## 有用的书籍
《了不起的Markdown》：
* [京东](https://item.jd.com/12669274.html)
* [当当](http://product.dangdang.com/27912444.html)

---

# Markdown标记
Markdown 标题有两种格式。  
## 1、使用 = 和 - 标记一级和二级标题
= 和 - 标记语法格式如下：  

    我展示的是一级标题
    =================

    我展示的是二级标题
    -----------------

显示效果如下图：

![md](https://www.runoob.com/wp-content/uploads/2019/03/01986C87-7E19-4497-878E-AE996AFC088E.jpg)

## 2、使用#号标记

使用 `#` 号可表示 1-6 级标题，一级标题对应一个 `#` 号，二级标题对应两个 `#` 号，以此类推。

    # 一级标题
    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题

显示效果如下图：
![effection](https://www.runoob.com/wp-content/uploads/2019/03/md2.gif)

---

# Markdown段落

Markdown 段落没有特殊的格式，直接编写文字就好，<B>段落的换行是使用两个以上空格加上回车。</B>

![img](https://www.runoob.com/wp-content/uploads/2019/03/36A89BDA-A062-4D66-A41B-0EBEE7891AB9.jpg)

当然也可以在段落后面使用一个空行来表示重新开始一个段落。

![img](https://www.runoob.com/wp-content/uploads/2019/03/3F254936-778E-417A-BEF2-467116A55D00.jpg)

---

## 字体

Markdown 可以使用以下几种字体：

    *斜体文本*
    _斜体文本_
    **粗体文本**
    __粗体文本__
    ***粗斜体文本***
    ___粗斜体文本___

显示效果如下所示：

---

![img](https://www.runoob.com/wp-content/uploads/2019/03/md3.gif)

---

## 分割线

你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：

    ***

    * * *

    *****

    - - -

    ----------

显示效果如下所示：

![img](https://www.runoob.com/wp-content/uploads/2019/03/3F46EAA9-DADE-48FD-99AA-DF7BEBFAA4FA.jpg)

---

## 删除线

如果段落上的文字要添加删除线，只需要在文字的两端加上两个波浪线 ~~ 即可，实例如下：

    RUNOOB.COM
    GOOGLE.COM
    ~~BAIDU.COM~~

显示效果如下所示：

![img](https://www.runoob.com/wp-content/uploads/2019/03/B5270A31-15D0-410B-AE1D-B9655B8F331C.jpg)

---

## 下划线

下划线可以通过 HTML 的 `<u>` 标签来实现：

    <u>带下划线文本</u>

显示效果如下所示：

![img](https://www.runoob.com/wp-content/uploads/2019/03/05A27273-B66D-43DE-A3DB-0D32FF024093.jpg)

## 脚注

脚注是对文本的补充说明。  
Markdown 脚注的格式如下:

    [^要注明的文本]

以下实例演示了脚注的用法：

    创建脚注格式类似这样 [^RUNOOB]。

    [^RUNOOB]: 菜鸟教程 -- 学的不仅是技术，更是梦想！！！

演示效果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/md5.gif)

---

# Markdown 列表

Markdown 支持有序列表和无序列表。  
无序列表使用星号(`*`)、加号(`+`)或是减号(`-`)作为列表标记，这些标记后面要添加一个空格，然后再填写内容：

    * 第一项
    * 第二项
    * 第三项

    + 第一项
    + 第二项
    + 第三项


    - 第一项
    - 第二项
    - 第三项

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/89446A8E-6D83-4666-AACC-980145D5F070.jpg)

有序列表使用数字并加上 `.` 号来表示，如：

    1. 第一项
    2. 第二项
    3. 第三项

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/560384BB-2B00-41D5-ACF2-18972F7F2775.jpg)

## 列表嵌套
列表嵌套只需在子列表中的选项前面添加四个空格即可：

    1. 第一项：
        - 第一项嵌套的第一个元素
        - 第一项嵌套的第二个元素
    2. 第二项：
        - 第二项嵌套的第一个元素
        - 第二项嵌套的第二个元素
    
显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/8ED795DA-F124-4E70-BA71-57CD9CF958A4.jpg)

---

# Markdown 区块
Markdown 区块引用是在段落开头使用 `>` 符号 ，然后后面紧跟一个空格符号：

    > 区块引用
    > 菜鸟教程
    > 学的不仅是技术更是梦想

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/DFE1124E-BC38-4C12-B7AC-053E560D4C9C.jpg)

另外区块是可以嵌套的，一个 `>` 符号是最外层，两个 `>` 符号是第一层嵌套，以此类推：

    > 最外层
    > > 第一层嵌套
    > > > 第二层嵌套

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/AA0A4A6A-33A7-48C7-971F-73FFC8FE85B0.jpg)

## 区块中使用列表
区块中使用列表实例如下：

    > 区块中使用列表
    > 1. 第一项
    > 2. 第二项
    > + 第一项
    > + 第二项
    > + 第三项

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/E3BF6399-6483-4C7A-8502-AE75E8D66C96.jpg)

## 列表中使用区块
如果要在列表项目内放进区块，那么就需要在 > 前添加四个空格的缩进。

列表中使用区块实例如下：

    * 第一项
        > 菜鸟教程
        > 学的不仅是技术更是梦想
    * 第二项

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/1B894FB4-53AC-4E2D-BA30-F4AE4DFA8B97.jpg)

---

# Markdown 代码
如果是段落上的一个函数或片段的代码可以用反引号把它包起来（\`），例如：

    `printf()` 函数

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/C928FDA3-E0A7-4AFF-AB2A-B3AF44F93DF9.jpg)

## 代码区块
代码区块使用 4 个空格或者一个制表符（Tab 键）。

实例如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/55EDFE05-5F27-458E-AFE0-7B96685C9603.jpg)

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/6DC89E5C-B41A-4938-97D8-D7D06B879F91.jpg)

你也可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）：

    ```javascript
    $(document).ready(function () {
        alert('RUNOOB');
    });
    ```

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/88F52386-2F98-4D7E-8935-E43BECA6D868.jpg)

---

# Markdown 链接
链接使用方法如下：

    [链接名称](链接地址)

    或者

    <链接地址>
例如：

    这是一个链接 [菜鸟教程](https://www.runoob.com)
显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/49E6CB42-F780-4DA6-8290-DC757B51FB9A.jpg)

直接使用链接地址：

    <https://www.runoob.com>

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/9BFF60A1-DD71-4B63-987B-4665B31C7787.jpg)

## 高级链接
我们可以通过变量来设置一个链接，变量赋值在文档末尾进行：

    这个链接用 1 作为网址变量 [Google][1]
    这个链接用 runoob 作为网址变量 [Runoob][runoob]
    然后在文档的结尾为变量赋值（网址）

    [1]: http://www.google.com/
    [runoob]: http://www.runoob.com/

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/EC3ED5D2-4F0D-492A-81B3-D485623D1A9E.jpg)

# Markdown 图片
Markdown 图片语法格式如下：

    ![alt 属性文本](图片地址)

    ![alt 属性文本](图片地址 "可选标题")

* 开头一个感叹号 !
* 接着一个方括号，里面放上图片的替代文字
* 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。

使用实例：

    ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

    ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/A042DF30-C232-46F3-8436-7D6C35351BBD.jpg)

当然，你也可以像网址那样对图片网址使用变量:

    这个链接用 1 作为网址变量 [RUNOOB][1].
    然后在文档的结尾为变量赋值（网址）

    [1]: http://static.runoob.com/images/runoob-logo.png

显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/75AA6EBF-CC57-44A6-A585-5EE3DD94E42A.jpg)

Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的 <img> 标签。

    <img src="http://static.runoob.com/images/runoob-logo.png" width="50%">
显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/55F2A67D-F4BD-4960-AC55-DC690A415878.jpg)

---

# Markdown 表格
Markdown 制作表格使用 `|` 来分隔不同的单元格，使用 `-` 来分隔表头和其他行。

语法格式如下：

    |  表头   | 表头  |
    |  ----  | ----  |
    | 单元格  | 单元格 |
    | 单元格  | 单元格 |
以上代码显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/23EACC50-38E0-4284-B99A-6BC22E284BAC.jpg)

对齐方式

__我们可以设置表格的对齐方式：__

* `-:` 设置内容和标题栏居右对齐。
* `:-` 设置内容和标题栏居左对齐。
* `:-:` 设置内容和标题栏居中对齐。

实例如下：

    | 左对齐 | 右对齐 | 居中对齐 |
    | :-----| ----: | :----: |
    | 单元格 | 单元格 | 单元格 |
    | 单元格 | 单元格 | 单元格 |

以上代码显示结果如下：

![img](https://www.runoob.com/wp-content/uploads/2019/03/87DE9D5C-44FB-4693-8735-194D3779EC3E.jpg)

# Markdown 高级技巧
## 支持的 HTML 元素
不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。

目前支持的 HTML 元素有：```<kbd> <b> <i> <em> <sup> <sub> <br>```等 ，如：

    使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

输出结果为：

![img](https://www.runoob.com/wp-content/uploads/2019/03/81999271-F914-428D-B7BF-164BDC67CAAC.jpg)

## 转义
Markdown 使用了很多特殊符号来表示特定的意义，如果需要显示特定的符号则需要使用转义字符，Markdown 使用反斜杠转义特殊字符：

    **文本加粗** 
    \*\* 正常显示星号 \*\*

输出结果为：

![img](https://www.runoob.com/wp-content/uploads/2019/03/CA0E0162-0C48-41CD-B57A-CB32A4287C02.jpg)

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

    \   反斜线
    `   反引号
    *   星号
    _   下划线
    {}  花括号
    []  方括号
    ()  小括号
    #   井字号
    +   加号
    -   减号
    .   英文句点
    !   感叹号

## 公式
__Markdown Preview Enhanced__ 使用 [KaTeX](https://github.com/Khan/KaTeX) 或者 [MathJax](https://github.com/mathjax/MathJax) 来渲染数学表达式。

KaTeX 拥有比 MathJax 更快的性能，但是它却少了很多 MathJax 拥有的特性。你可以查看 KaTeX supported functions/symbols 来了解 KaTeX 支持那些符号和函数。

默认下的分隔符：

* ```$...$ 或者 \(...\) 中的数学表达式将会在行内显示。```

* ```$$...$$ 或者 \[...\] 或者 \`\`\`math 中的数学表达式将会在块内显示。```

![img](https://www.runoob.com/wp-content/uploads/2019/03/0e408954-fda8-11e5-9eb4-562d7c0ca431.gif)

    $$
    \begin{Bmatrix}
    a & b \\
    c & d
    \end{Bmatrix}
    $$
    $$
    \begin{CD}
    A @>a>> B \\
    @VbVV @AAcA \\
    C @= D
    \end{CD}
    $$

输出结果为：

![img](https://www.runoob.com/wp-content/uploads/2019/03/A9031CEB-04DB-4822-9C98-2E99489D3662.jpeg)

---