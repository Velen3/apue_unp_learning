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

