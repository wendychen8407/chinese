> -  原文地址：[How to Learn Programming – The Guide I Wish I Had When I Started Learning to Code](https://www.freecodecamp.org/news/how-to-learn-programming/)
> -  原文作者：[Jacob Stopak](https://www.freecodecamp.org/news/author/initialcommit/)
> -  译者：Papaya Huang
> -  校对者：

![How to Learn Programming – The Guide I Wish I Had When I Started Learning to Code](https://www.freecodecamp.org/news/content/images/size/w2000/2021/09/The-Programming-Guide-I-Wish-I-Had-When-I-Started-1.png)

仅仅只是想到学习编程这个概念就让人畏惧，**代码**非常神秘，仿佛是一种与机器交流而不是让人去理解的技术。

大多数人采用的学习编程的方式是挑一个流行的编程语言，然后一头扎进去。具体的表现形式可以是选一门线上的编程课程、教学项目，或者随机购买一个编程话题相关的书籍。

极少的准开发者会从一个路线图开始，路线图相当于编码世界的一张鸟瞰图，梳理了一些相关的编程概念、语言以及几乎100%的开发者每天都会使用的工具。

在这篇文章中，我将提出一种路线图。我梳理出来了专业开发者用来编写代码、合作和创建专业项目的14个步骤（每一个步骤探讨了一个关键的概念、语言或者工具）。

我精心挑选出来的这14个步骤是基于我长达20年的个人学习代码的经历。

我花了这么长时间才使自己在开发的时候感觉自在，一部分原因是我曾经只专注于具体的话题，而没有从更广阔的角度来看整个编码世界。

本文的每一个步骤所讨论的“代码重点”是你开始编程之旅**起码要知道**的概念。

我想在正式开始之前最后强调一点，你肯定不会因为这篇文章成为编程专家，这篇文章的本意也并非如此。这篇文章的目的是为了让你知道有这些内容，以及这些内容背后的运行逻辑，给你继续前行打下基础。

## 给初级开发者的14步路线图

1.  [熟悉计算机系统结构和数据基础](#1-familiarize-yourself-with-computer-architecture-and-data-basics)
2.  [了解编程语言的运作](#2-learn-how-programming-languages-work)
3.  [理解互联网的运作](#3-understand-how-the-internet-works)
4.  [练习基本的命令行](#4-practice-some-command-line-basics)
5.  [使用Vim来培养你的文本编辑器技能](#5-build-up-your-text-editor-skills-with-vim)
6.  [学习一点HTML](#6-take-up-some-html)
7.  [处理一些CSS](#7-tackle-some-css)
8.  [由JavaScript开始编程](#8-start-programming-with-javascript)
9.  [使用Python继续编程](#9-continue-programming-with-python)
10.  [进一步了解Java](#10-further-your-knowledge-with-java)
11.  [使用Git跟踪代码](#11-track-your-code-using-git)
12.  [使用数据库和SQL存储数据](#12-store-data-using-databases-and-sql)
13.  [阅读Web框架和MVC](#13-read-about-web-frameworks-and-mvc)
14.  [玩转包管理工具](#14-play-with-package-managers)

话不多说，让我们开始吧！

<h2 id="1-familiarize-yourself-with-computer-architecture-and-data-basics"> 1)熟悉计算机系统结构和数据基础</h2>

现代编程语言美妙的原因之一是在创建精美的应用的时候，它们帮助我们免去幕后繁琐的硬件细节。（大部分情况是这样）

这种能力被称为**抽象**——使用高级工具（这里指编程语言）的能力，可以简化理解、缩小所需掌握技能范围。

但这并不意味着了解机器本身一无是处。至少可以帮助你在工作场所和同事畅谈高CPU和内存使用率。

以下是计算机基础的基本知识：

计算机最重要的部分位于**微芯片**（也称为**集成电路**）。

微芯片依靠**晶体管**的电子元件来发挥作用。晶体管是微小的电子开关，在给定时间内处于关（0）或者开（1）的状态。单个微芯片嵌入了上百万甚至术十亿的晶体管。

大部分现代计算机有一个叫做**中央处理器（CPU）**的微芯片。你可以把这个当作计算机的大脑。它处理大部分数字运算和逻辑任务。

每一个CPU有一个**指令集**，是供CPU理解的二进制（0和1）指令的合集。幸运的是，作为软件开发人员，我们并不需要担心自己不理解这些指令，这就是抽象的力量。

如果说CPU是大脑的逻辑中心的话，那么我们还需要一个存储器来短期或长期地存储记忆。

计算机拥有**随机存取存储器（RAM）**作为“工作存储器“(或者叫做短期存储器)来存储程序运行时使用的信息。

RAM是由一组**内存地址**组成，可用于存储数据位。在像C语言这样的历史久远的计算机语言中，程序员确实可以使用**指针**来直接处理内存地址，但是这在现代语言中很少见了。

最后这个组件你肯定熟悉——硬盘驱动。硬盘相当于人类大脑的长期记忆。硬盘是存储数据的内部和外部设备，即便关机了，这些数据仍然存在。

在我们正式介绍编程语言细节之前，让我们花点时间了解一下数据，**数据**这个词到底代表了什么？

从表面来看，我们会想到文本文件、图像、视频、电子邮件、文件和文件夹。这些都是我们每天在计算机上创建和存储的高级数据结构。

但位于底层的计算机芯片（CPU或者RAM芯片）并不知道什么是“图片”或者“视频”。

从芯片的角度来看，这些数据结构被作为一长串0和1存储了起来，这些0和1被称为**位**。

位通常以一组八位的形式存储，称为一个 **字节**。 一个字节就是一个简单的八位序列，例如 `00000001`、 `01100110` 或 `00001111`。这样表示信息的方法被称为 **二进制表示法**。

<h2 id="2-learn-how-programming-languages-work"> 2)了解编程语言的运作</h2>

在上一章节，我们提到了大部分计算机以依赖于CPU，CPU可以理解一串特定的0和1。

因此，理论上我们可以编写一串由0和1组成的代码告诉CPU要做什么。以二进制形式编写的指令被称为**机器码**。

写这样的代码听上去相当可怕，反正我没试过，因为我使用高级编程语言如：JavaScript、Python和Java。

**高级编程语言**提供一组人类可以读取的关键字、声明和语法规则，使得人们可以更加容易地学习、改bug和使用。

编程语言提供一座桥梁连接人类大脑和计算机大脑（CPU）。

我们编写的代码最终会转换为CPU理解的二进制指令（机器码）。

根据你选择的语言，我们可以认为你的代码要么被**编译**，要么被**解释**为可以被CPU执行的机器码。大多数编程语言都包含一个**编译器**或者**解释器**来执行这个翻译步骤。

举几个例子——JavaScript和Python是解释型语言，然而Java是编译型语言。一个语言是否为编译型或者解释型语言（或者两者结合）会对开发者的编写便利性、处理错误的方法和程序的性能造成影响。这里我们不赘述。

<h2 id="3-understand-how-the-internet-works"> 3)理解互联网的运作</h2>

不论你渴望开发什么类型的程序，你都会遇到计算机之间相互交流的场景，这个场景就发生在互联网。

互联网是一个连接了全球计算机的集合。也可以被认为是一个全球性的网络。互联网内部的每一台计算机都遵循特定的规则来达成彼此间交流，对于计算机来说，“交流”就是交换数据。

如我们在之前章节介绍的那样，所有数据类型（网页、图像、视频、电子邮件等）都可以被0和1来表示。

因此，你可以把互联网当作一个巨大的计算机集合，这些计算机之间相互传输0和1，数据以0和1的形式存储，互联网就是一个数字对话媒介。

如果互联网是一个巨大的对话场所，那让我们来定义一下对话的参与者。

首先，让我们引入一个类比：大部分人类的对话需要至少两个参与者。一个发起对话，一个回应对话，假设这两个人都在场并且有空。

而从互联网的角度来看，发起对话的计算机被称为**客户端**，回应或者应答对话的计算机被称为**服务器**。

假设你打开了浏览器，并且搜索了 "www.google.com"。 在这个场景内，你的浏览器就是客户端，更宽泛地讲，你可以把你正在使用的计算机当作客户端。

再抽象一点，**你**就是客户端，因为你开启了对话。是你在搜索框输入了 "www.google.com"，并点击了回车键，你的电脑才向某台谷歌的计算器发出对话请求。

谷歌的计算机就被称为服务器。它通过发送被请求的数据，并且在数据在你的浏览器显示来回应。然后嗒哒！你眼前出现谷歌的网页。所有互联网数据传输都使用这种客户端/服务器关系。

<h2 id="4-practice-some-command-line-basic">练习基本的命令行</h2>

乍一看，**命令行**可能让人生畏。命令行往往出现在电影的画面里，在黑色的屏幕上滚动着让人无法理解的文字、数字和符号，人们往往把它和邪恶的黑客或者天才技术伙伴联系到一起。

骑士不需要多么天才的头脑就能够理解并且使用命令行。命令行可以执行我们习惯用鼠标勾选点击的一些日常任务。

主要的区别在于，命令行主要通过键盘来输入，一旦你掌握了它，可以大大提高效率。

你可以使用命令行来浏览文件夹、列出文件夹内容、创建新的文件夹、复制和移动文件、删除文件、执行程序等等。输入命令行的窗口被称为**终端**。

让我们来通过一个基础的导航命令行教程来了解如何使用命令行。

当你打开终端的时候，你首先会冒出一个问题 "_我在哪儿"?_ 我们可以使用 `pwd`命令行 (相当于 “打印正在工作的目录（”Print Working Directory))来解决这个问题。 这个命令行会打印出你当前所在文件夹位于整个文件系统的位置。

动起手来：

### 如何使用命令行

如果你是Mac用户，打开终端应用，它本质上是一个Unix命令行终端。

如果你使用非GUI（图形用户界面）的操作系统，例如Linux或Unix，则在默认情况下，启动计算机就是命令行。如果你的Linux或者Unix系统有GUI，你需要手动打开终端。

在提示符下，输入`pwd`并按下回车，命令行会打印出你当前所处的文件夹的路径。

默认情况下，打开命令行时激活的文件夹是登陆用户的主目录。如果你想从别的位置开始，可以自定义。

方便起见，可以使用波浪号`~`字符来表示主目录。我们将在接下来的几个示例中使用它。

现在我们知道我们在哪儿了，就可以使用 `ls`命令来列出当前目录的内容。 `ls` 命令代表了“清单（list）”。

输入`ls`并点击回车， 当前目录名下的所有内容(文件和副目录)都会显示在屏幕上。

输入`ls -al`重新运行上面的命令，并点击回车。你会得到更多有关当前目录的信息，包括文件大小、修改时间和文件权限。

上面命令中的连字符`-`使得我们可以通过添加小标来改变命令行为。在上述例子中我们添加了`-a`标记来显示目录所有内容(包括隐藏文件)，同时`-l`标记显示文件其他信息。

然后我们通过`mkdir`命令来创建新文件夹，这个命令是 "Make Directory"（创建目录）。我们将创建一个叫做"testdir"的目录。

输入`mkdir testdir`并点击回车，然后输入`ls`并点击回车，你将在清单中看到你新创建的目录。

要一次性创造嵌套目录，可以使用`-p`标记来创建整个目录链，如：`mkdir -p directory1/directory2/directory3`。

如果只在一个固定位置使用命令行的话，用处不大，所以我们接下来将学习如何在文件系统的不同目录间切换。我们可以通过`cd`命令来实现，它代表了 "Change Directory"（更改目录）。

首先，输入`cd testdir`然后点击回车。再输入`pwd` 并点击回车。注意此时的输出告诉我们正在"testdir"目录内。我们进入了这个目录！

输入`cd ..`点击回车，`..`告诉命令行回到父目录。

再输入`pwd`点击回车。注意此时的输出告诉你我们回到了原目录，我们回去了！

接下来我们将学习如何在当前目录创建全新的空文件。

输入`touch newfile1.txt`并点击回车。你可以使用`ls`来检查新文件是否已经创建。

接下来我们使用`cp`命令来将文件从一个文件夹复制到另一个文件夹。

输入`cp newfile1.txt testdir`并点击回车。使用`ls`和`ls testdir`检查这个新文件是否还在当前文件夹，以及是否被复制到了 "testdir" 目录。

我们也可以使用`mv`命令来移动文件。

输入`touch newfile2.txt`点击回车创建新的文件。
然后输入`mv newfile2.txt testdir`点击回车将文件移动到"testdir"文件夹。

使用`ls`和`ls testdir`来检查文件是否已经移动到"testdir"文件夹(该文件应该已不存在于原始目录，因为它被 _移动了_ 而并非复制)。

`mv`也可以用来重命名文件。

输入`touch newfile3.txt`点击回车来创建一个新文件。然后输入 `mv newfile3.txt cheese.txt`点击回车来更新文件名。使用`ls`检查文件是否被重命名。

最后我们可以使用`rm`命令来删除文件。

输入`rm cheese.txt`点击回车删除文件。使用`ls`检查文件是否被删除了。

输入`rm -rf testdir`点击回车来删除"testdir" 目录及名下文件。使用`ls`目录是否被删除。

注意我们必须使用`-rf`标记来删除目录。这样才可以彻底清空文件夹。

<h2 id="5-build-up-your-text-editor-skills-with-vim"> 5) 使用Vim来培养你的文本编辑器技能</h2>

我们已经学习了命令行的基本知识，并且练习了如果不使用鼠标来控制文件。

虽然我们已经知道如何使用命令行创建、复制、移动、重命名以及删除文件，但是我们还不知道如果使用终端来编辑文本内容。

使用终端来编辑文件非常重要，因为计算机代码就是存储在有组织的文件中的文本。

我们当然可以使用一些华丽的文本编辑器如微软的word(或者更适合于代码的编辑器如Sublime或Atom)来编写我们的代码，但这不是必须的。我们已经使用终端来运行命令行了，显然终端是最方便编辑代码的地方。

有优秀的文本编辑器，但是我推荐你[通过Vim来打基础](https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/)。

Vim是最早的一批编辑器，并且经受住了时间的考验。[Vim](https://zh.wikipedia.org/zh-tw/Vim)代表 "**_VI_** i**_M_**proved"，因为它由**_Vi_**发展而来的。

如上文所述，Vim是可以直接在终端运行的编辑器，所以我们不需要额外打开一个窗口并使用鼠标来操作。Vim提供一组命令行和模式使得我们可以直接使用键盘来创建和编辑文本。

Vim[有一定的学习曲线](https://www.freecodecamp.org/news/how-not-to-be-afraid-of-vim-anymore-ec0b7264b0ae/)，但是只要稍微练习，你整个程序员职业生涯都会受益。

许多系统都预装了Vim，若要检查你的计算机是否安装了Vim，可以使用命令`vim -v`。

如果终端打开了Vim并且显示了版本，你就可以开始使用了。如果没有，就需要手动安装 (注意你可以通过输入`:!q`并点击回车来退出Vim)。更多安装Vim的信息，可以查看 https://vim.org。

我认为学习Vim最快速简单的方法是使用内置的**VimTutor**。运行前请确认系统已安装Vim，打开命令行输入`vimtutor`点击回车。

这个教程已经非常棒了，所以这里就不再赘述，现在打开你的VimTutor开始学习吧！我们下一章节见！

如果完成了VimTutor之后你还有精力学习更多内容的话，欢迎查看[7个大幅提升效率的Vim命令](https://initialcommit.com/blog/7-versatile-vim-commands)。

<h2 id="6-take-up-some-html"> 6)学习一点HTML</h2>

你可以将HTML（**H**yper**T**ext **M**arkup **L**anguage（超文本标记语言）的缩写）视为网页的骨骼。它通过指定应该显示的元素及显示的顺序来确定页面的结构。

你浏览过的所有页面都和HTML多少有点关系。每当你浏览一个网页，托管网页的服务器就会传输一些HTML到达你的浏览器。浏览器读取这些HTML并展示出来。

大多数网页包含一组相当标准的内容，包括标题、文本内容、图像链接、导航链接、页眉和页脚等等。所有这些信息都存储为HTML，定义页面的结构。

需要注意的是HTML实际上并不是一种编程语言，虽然我们常常称它为"HTML代码"。

在后面的文章我们将看到其他编程语言具备**行为**，如执行一系列指令。HTML并不**做**任何事。我们不运行或执行HTML，HTML就在那儿等着被发送给浏览器，再显示在用户端。

事实上，HTML基本上只是数据。它是定义网页应该是什么样子的数据，仅此而已。

如何编写HTML呢？HTML使用一组**标签**(基本是一组标记)对应可以标记网页的元素。标签使用尖括号标记。

比方说，**title（标题）**标签写做`<title>My Page Title</title>`以及 **paragraph（段落）**标签写做`<p>A bunch of random text content.</p>`。

每一个HTML元素都有一个起始标签和一个结束标签。起始标签是由一组尖括号和标签名组成：

`<tagname>`

结束标签和起始标签类似，只是多了一个正斜杠，来表示这是结束标签。

`</tagname>`

两个尖括号之间的任意文本就是要在网页上显示的内容。

让我们认识一下最常见的几个标签。 首先是`<html>`标签，定义了HTML页面的开始。对应的`</html>` 标签 (注意正斜杠) 定义HTML页面的结束。 两个标签之间的任意内容都属于页面。

第二个要介绍的是`<head>`标签。它定义了浏览器读取页面需要的额外信息。这里的大部分内容都不会展现给用户。对应的`</head>`标签定义了HEAD部分的结束。

在上文中提到了`<title>`标签。它定义了页面的标题，会在浏览器的选择卡中显示。这个标签要在`<head>...</head>`内部使用。

接下来是`<body>`标签。该标签内部的所有内容就是网页的主要内容。将这四个标签放置在一起的结构如下：

```html
<html>
    
    <head>
        <title>My Page Title</title>
    </head>
        
    <body>
        <p>A bunch of random text content.</p>
    </body>

</html>
```

上面简单的HTML代码块展现了一个包含一个标题和一个段落的网页。

从这个例子我们可以看出HTML标签可以相互嵌套。也就是HTML标签可以放置在其他标签内部。

HTML提供了一系列标签供用户使用，我们不会逐一讲解，我只列举了一部分：

-   `<p>`: 开启新一行的段落
-   `<h1>`: 页面标题(heading)通常用作页面标题(title)
-   `<h2>`: 段落标题（heading)通常用作段落标题(title)
-   `<hx>`:  _x_ 表示3到6之间的数字，代表级别更小的标题（heading）
-   `<img>`: 一个图片
-   `<a>`: 一个链接
-   `<form>`: 表单，包含供用户填写和提交的字段或输入框
-   `<input>`:供用户输入信息的输入字段，通常在表单中
-   `<div>`: 内容划分，用于将几个其他类型元素组合在一起，有一定间距
-   `<span>`: 另一个分组元素，但用于将文本短语包装在另一个元素中，通常仅限于应用于文本内容的特定部分的特定格式

<h2 id="7-tackle-some-css">7)处理一些CSS</h2>

缺少CSS（**C**ascading **S**tyle **S**heets层叠样式表）网页就像没有裱花的蛋糕。虽然也可以吃，但是索然无味。

CSS使得我们可以将样式的属性，如：背景色、字号、宽度、长度和HTML元素关联起来。

样式属性告知浏览器如何渲染对应的效果。和HTML一样，CSS并不是一门编程语言，它并不具备行为，但是可以给HTML骨骼添加样式。

让我们看看如何给HTML添加CSS样式，有三个重要的部分：

**CSS选择器:** 标记我们需要添加样式的HTML元素

**CSS属性名:** 我们要添加到响应的HTML元素的特定样式属性的名称

**CSS属性值:** 我们要应用的样式属性的值

以下是将这三个部分组合在一起来定义一个段落的颜色的字体大小：

```css
p {
  color: red;
  font-size: 12px;
}
```

让我们从头开始，在花括号之前是CSS选择器。在示例中**p**代表的是`<p>`(paragraph)这个HTML标记。也就是说网页中所有`<p>`标签都要应用这个样式。

我们来看看花括号里面发生了什么——我们想要应用到目标元素的样式。

CSS属性和值用冒号隔来。属性(示例中的"color"和"font-size")在左手边，属性的值(示例中的"red""12px")在右手边。每一个属性名/值对由一个分号结尾。

你应该已经看出来这是如何运作的，css代码块告诉浏览器使用红色、字号为12px样式来修饰`<p>`内的内容。 

那HTML如何包含这些CSS样式呢？使用`<link>` HTML标签。通常，会有一个独立的CSS文件 (**.css**文件)。也就意味着我们需要引入到HTML文件中，这样浏览器才会知道CSS文件的存在。

`<link>`标签就服务于这个目的。我们在`<head>`部分加入`<link>`元素，特指需要被引入的CCS文件：

```css
<head>

    <title>My Page Title</title>

    <link rel="stylesheet" type="text/css" href="/home/style.css">

</head>
```

在这个示例中，我们使用**href**标签来引入CSS文件：_/home/style.css_。

在接下来的三个部分，我们（终于）要进入编程语言了！

我们将大概介绍一个JavaScript、Python和Java以及一些重要的编程概念。我们将通过代码示例来比较三种语言的相同和不同，给你进一步了解这三种语言打下基础。

<h2 id="8-start-programming-with-javascript">由JavaScript开始编程</h2>

让我们先回答这个问题：如果HTML是网页骨架、CSS是样式，那我们还需要JavaScript做什么？

答案是我们可以不需要JavaScript，一个样式好看的静态网站已经足够，所以只需要HTML和CSS就够了。

这个答案的关键词是“静态”，如果想要给网页添加一些动态效果的话，如改变文本或者添加更为复杂的用户交互，我们就需要使用JavaScript。

### 什么是JavaScript?

JavaScript到底是什么呢？JavaScript是专为互联网和网站而创建的编程语言。在第二部分我们提到过，大多数编程语言要么就是被编译要么就是被解释，程序基本上独立运行。

JavaScript在这点上有些与众不同，它被设计为直接在网络浏览器内部运行，我们可以编写代表一组行为的代码，直接在网页上执行，使得网站更加动态。

你可以使用后缀为`.js`的文件来编写JavaScript代码或者直接在HTML的`<script>`标签内编写JavaScript。

JavaScript在很长时间内都只能在浏览器内部运行，但是**Node.js**改变了这一运行范式，之后JavaScript就拥有了独立运行的环境。

除了在浏览器内部（即客户端）运行，Node.js可以被安装在任何计算机，创建运行JavaScript的环境。你也可以在网络服务器安装Node，这样JavaScript不仅可以编写前端代码也可以编写后端代码。

在讲解了JavaScript基础之后，让我们来看看JavaScript的一些主要概念。

### JavaScript中的变量和赋值 

变量或许是编程中最为基础的概念。变量是用来引用特定值的一个名称或者占位符。

**变量**这个名称意味着，在程序执行的过程中，变量内部存储的值可以发生改变。

可以使用变量存储数字、字符串、列表以及其他数据结构，我们之后会详细说明。

所有编程语言都包含变量，只是语法上有些微不同。

我们可以在整个代码中引用变量的值，所以变量十分有用。我们可以检查我们需要的变量的值，根据变量的改变来执行不同的行为。

在JavaScript中我们使用`let`关键字来声明变量，如：`let x;`。

这样`x`这个变量就可以在代码中使用。注意我们在末尾添加了分号结束。在JavaScript(以及其他一些语言中)分号代表了声明的结束。

我们已经创建了变量 _x_，就可以使用等号给这个变量赋值，等号又可以称为 **赋值操作符**: `x = 10;`

我们将数字10赋值给名为 _x_ 的变量。无论何时我们在代码中使用 _x_ ，就会得到10。

变量声明和赋值可以在一行内进行：

```javascript
let x = 10;
```

### JavaScript的数据类型

在上一部分，我们将整数存储到了命名为 _x_ 的变量。我们也可以存储十进制数，或者**浮点数**。我们可以这样写: `let x = 6.6;`。

能够被存储的不同的值被称为**数据类型**。现在我们只看到了数字类型(整数和浮点数)，我们只触及了表面，我们也可以在变量中存储文本。

在代码术语中，一段文本被称为 **字符串**。我们可以将字符串存储到变量x中，使用单引号或者双引号来框住字符串。 

```javascript
let x = 'Hello there!';

let y = "Hey bud!";
```

接下来我们要讨论**布尔值**。布尔值只有`true`或`false`两个值 – 必须小写。在JavaScript中，true和false是专门用于表示布尔值的关键字。

```javascript
let x = true;

let y = false;
```

注意`true`和`false`并没有字符串那种引号。如果使用了引号，就不是布尔值，而是字符串。

我们经常使用布尔值来控制条件（if/else）语句中的程序流，接下来我们讲学习程序流。

### JavaScript中的程序流控制语句

现在我们已经了解了变量和基本的JavaScript数据类型，让我们来看看我们可以用它们做些什么。

如果不告诉程序我们要用变量做什么，变量就没太大用处。我们可以使用**语句**来让变量做事情。

语句是特殊关键字，允许我们在代码中执行某些操作，这些操作通常基于我们定义的变量的值。语句让我们定义程序的逻辑流程，并执行许多有用的操作，这些操作将决定我们的程序如何工作。

#### If / Else语句

我们首先讨论 `if`语句。如果条件为真，`if`语句允许我们做某事。如下：

```javascript
let x = 10;

if ( x > 5 ) {
    console.log('X is GREATER than 5!');
} else {
    console.log('X is NOT GREATER than 5!');
}
```

我们创建一个命名为 _x_ 的变量并赋值为10， 然后使用 `if`语句。 在 `if`关键字之后，是一组括号，括号内部是有待评估的条件，示例中是`x > 5`。 _x_ 被赋值为10，所以示例中的条件为真。

因为条件为真，所以花括号中的代码将执行，我们会看到 "X is GREATER than 5!" 被打印出来。(我们尚未讨论 `console.log()`的意思， 现在我们只知道它会打印括号里的内容）。

在该示例中，我们还使用了`else`语句。若条件为`false`，则执行内部的代码。

#### While循环

我们接下来要讨论**while循环**。 循环使得我们在不需要赋值和粘贴代码的情况下，反复执行同一块代码。

假设我们想要打印一句话五次，我们可以这样操作：

```javascript
console.log('This is a very important message!');
console.log('This is a very important message!');
console.log('This is a very important message!');
console.log('This is a very important message!');
console.log('This is a very important message!');
```

这样可以打印5次，那如果是100次，1000次呢？我们需要更好的方式来重复，循环就派上用场。在代码术语中，重复一段代码被称为**遍历**。

`while`循环将在条件为真的时候不断循环：

```javascript
let x = 1;

while ( x <= 100 ) {
    
    console.log('This is a very important message!');
    
    x = x + 1;
    
}
```

在该示例中，我们将 _x_ 的初始值设定为1， 然后编写一个`while`循环。和`if`语句一样，我们将条件写在括号内。示例中的条件为`x <= 100`。 只要 _x_ 小于等于100，条件就一直为`true`。

然后我们在花括号内部写需要执行的代码。首先在控制台打印信息，然后使 _x_ 增加1。

循环会再次评估条件是否为`true`。此时 _x_ 值为2，因为第一次循环结束后增加了1。2小于100所以条件仍为`true`。

循环中的代码不断执行直到 _x_ 值为101。这时，_x_ 比100大，条件为 `false`。循环停止执行。

### HTML的<script>标签

我们已经介绍了JavaScript，如何将JavaScript添加到HTML页面？我们可以使用之前未讨论到的`<script>`标签。

和`<link>`类似，`<link>`用于将CSS添加到HTML，而`<script>`专门用于添加JavaScript。

假设我们把上述代码保存为`customscript.js`文件，并放置在和HTML同一个文件夹中。我们可以在HTML的 `<head>...</head>` 部分添加JavaScript文件。

```html
<script type="text/javascript" src="customscript.js"></script>
```

当网页在浏览器中显示时执行时，会从这个文件中加载JavaScript代码，。

一旦熟悉了JavaScript的技巧，你可以[尝试搭建一些简单的初学者项目](https://www.freecodecamp.org/news/javascript-projects-for-beginners/)来进一步练习。

<h2 id="9-continue-programming-with-python"> 9)使用Python继续编程</h2>

我们已经学习了基础的JavaScript知识，这时开启一门新的语言十分有用，这门语言就是——Python。

大多数语言都具备一套同样的功能，包含：变量、算术运算符、if/else语句、循环和函数。

比较不同的语言如何实现同样的功能对于我们的学习十分有帮助。概念通常是相似的，但是语法（如何编写代码）有些微不同。

### 什么是Python?

我们先来介绍一下Python的背景知识。和JavaScript一样，Python也是一种高级编程语言，并且在设计上将“易开发”优先于“执行快”。

我认为Python是最适合初学者学习的编程语言之一。Python的语法十分简洁并且符合直觉，python在开源和商业领域都非常受欢迎。

我们对比过编译型语言和解释型语言，Python是一门解释型语言。运行Python程序的时候，**Python解释器**会主动处理并逐行在机器上执行代码。

和编译型语言不通的地方在于，编译型语言会先使用编译器将代码优化成更容易执行的形式，然后再执行。

和JavaScript不同的是，Python并不是直接在浏览器中运行的代码。Python被创建为一种便捷的 _脚本语言_——一种可用于执行任意任务的代码，通常在用户的本地计算机上执行。

Python代码可以在任何安装了Python解释器的计算机上执行。它是一种常用的脚本语言，但也广泛用于数据科学和服务器端的应用程序。

### Python中的变量与赋值

和JavaScript一样，Python也可以声明变量。可以直接使用等号来进行声明和赋值：

```python
x = 10
y = "cheese"
```

Python和JavaScript在定义变量的时候有两点不同：在Python中不需要使用`let`关键字，也不需要在每行结尾添加分号。

Python使用一组基于空格和缩进的语法规则。就不需要终止字符：分号；也不需要使用花括号来代表代码块。

### Python的数据类型

Python也有一组数据类型，我们可以将它们分配给变量。这些包括整数、浮点数（小数）、字符串、列表和字典。

整数、浮点数和字符串与JavaScript的相同，所以就不赘述。

Python中的布尔值与JavaScript非常相似，只是关键字True和False必须大写：

```python
x = True

y = False
```

### 程序流控制声明

与JavaScript一样，Python也流控制语句集，但语法略有不同。

#### If / Else语句

JavaScript`if/else`示例的等价Python示例如下：

```python
x = 10

if ( x > 5 ):
    print('X is GREATER than 5!')
    
else:
    print('X is NOT GREATER than 5!')
```

我们先定义一个名为 _x_ 的变量并并赋值为10，紧接着是`if`语句。因为括号内部的条件被评估为`True`，`if`语句后缩进的代码被执行。我们便看到屏幕上打印出'X is GREATER than 5!'。

在Python中`print()`函数打印内容。

同时也要注意`else`语句，如果 _x_ 条件为`False`，就会打印另外的语句。

Python代码和我们之前看到的JavaScript代码有两大不同：Python使用冒号而不是花括号来指示`if`语句的开始。

另外，在Python中`print()`函数的缩进对代码效果有影响。在JavaScript中，语句之间的缩进或空格无关紧要，因为JavaScript使用花括号标识代码块并使用分号标识语句的结尾。但是在这个Python 示例中，没有分号，也没有大括号！

这是因为Python实际上使用空格和换行符来标识语句和代码块的结尾。

冒号告诉Python解释器，`if`引导的代码块开始了。`if`之后的代码块必须缩进。(通常 1 tab = 4 空格)这样Python解释器才知道 `if` 的代码块在哪里。下一个未缩进的行意味着`if`代码块的结束。

#### While循环

接下来我将讨论Python中的while循环。Python中的 `while`循环大体和JavaScript中的一致，但是语法有所不同：

```python
x = 1

while ( x <= 100 ):
    print('This is a very important message!')
    x = x + 1

print('This is not in the loop!')
```

和JavaScript`while`循环不同的地方在于：

-   在定义变量的时候没有使用`let`
-   行末没有使用分号结束
-   用冒号取代花括号
-   循环内的代码块必须缩进

我们在循环之外打印了一条附加消息，以表明未缩进的代码行不是循环的一部分并且不会被重复。

我推荐Python初学者看一下[Python的禅意](https://initialcommit.com/blog/zen-of-python)，这篇文章介绍了编写Python代码的20条重要规则。

如果你已经掌握了Python的基础，[可以尝试搭建一些初学者的Python项目](https://www.freecodecamp.org/news/python-projects-for-beginners/)。

<h2 id="10-further-your-knowledge-with-java">10)进一步了解Java</h2>

我们已经了解了一组高级编程语言，让我们往后退一步，瞧一瞧Java。

JavaScript和Python实时通过解释器来执行源码。但Java是一门编译型语言，需要编译器(而不是解释器)将Java源码转换为计算机可以理解的代码。

大多数编译器会生成一个或多个由机器码组成的可执行文件，这些代码可以在编译它们的特定操作系统和硬件平台上运行。

但Java特殊的地方在于，它将源码转换为[**字节码**](https://zh.m.wikipedia.org/zh/Java%E5%AD%97%E8%8A%82%E7%A0%81)，这和其他编译型语言生成的的机器码不太一样，Java字节码需要在**Java虚拟器(JVM)**执行。

可以将JVM想象成你安装在电脑的一个程序，这个程序允许你执行Java字节码，当人们谈论 "_是否在电脑安装了Java_，" 他们指的是是否在电脑上安装了**JVM**。

JVM和我们在前面章节讨论的解释器的功能类似，但是它没有把源码 (存储在 .java 文件)当作输入，而是把编译过的字节码作为输入。

这种设置的好处是它允许在特定操作系统和平台上编译的字节码由任何其他平台上的JVM执行。

假设我们有一个Java代码文件，该文件在运行Windows操作系统的计算机上编写并编译为字节码。这个字节码可以被JVM在任何平台上执行（即程序运行），包括Windows、Mac OS、Linux等。

大多数编程语言并非如此，它们只能在编译它们的环境中执行。

### Java中的变量和赋值

Java和我们之前讨论的语言(Python和JavaScript)的一个主要的区别在于Java是**静态**语言。

这意味着我们的变量的数据类型必须在程序编译之前就建立并被理解。

每次我们在Java代码中创建变量时，都需要显式指定该变量的数据类型，例如整数、字符串等。这称为变量**声明**。

一旦我们声明了一个变量的数据类型，它就只能在整个程序执行过程中保存该类型的数据。

这与JavaScript和Python非常不同，它们的数据类型是在程序执行期间建立的，也称为**运行时**。因此，像JavaScript和Python这样的语言被称为**动态类型语言**——我们不会在源码中明确声明变量数据类型，也可以轻松地将变量动态地重新分配给任何类型。

在Java中声明变量：

```java
Datatype name = value;
```

`Datatype`指的是我们需要存储的变量类型，如：整数、字符串等。`name`代表变量的名称，我们会在之后的代码中使用。`value`是我们要赋值给变量的值。注意和JavaScript一样，所有Java声明结尾都要使用分号。

### Java中的数据类型

在Java中，内置的数据类型被称为**原始**数据类型，因为有Python和JavaScript的基础，这些数据类型对于我们来说，看起来非常熟悉。主要的原始类型有：

-   整数 `int`: 存储 −2,147,483,648 到 2,147,483,647之间整数。
-   浮点数 `float`: 存储 3.4x10^−038 到 3.4x10^038之间的浮点数。
-   布尔值 `bool`: 存储`true`或`false`。

请注意，还有一些其他的原始类型（short、long、byte 和 double）我们不会在这里介绍，因为不经常使用。以下展示我们如何初始化这些数据类型：

整数: `int x = 100;`

浮点数: `float pi = 3.14;`

字符: `char middleInitial = 'T';`

布尔值: `bool isHuman = true;`

我必须重申，一旦声明了变量的数据类型，该变量就只能保存指定数据类型的值。

例如，如果我们的程序试图将字符值存储在声明为整数的变量中，则会引发错误。在前面的示例中，我们不能将字符“S”分配给整数变量 _x_。

我们将讨论的下一个数据类型是字符串——表示为文本数据的一系列字符、数字或符号。

Java中的字符串是一种非原始数据类型，这意味着它们是由较小的部分组成的。要声明一个字符串变量，我们使用String数据类型并将分配的值放在双引号中：

```java
String name = "Harry Potter";
```

### Java中的程序流控制语句

与JavaScript一样，Java使用花括号来定义`if`语句、循环和函数的代码块。我们将使用前几章程序控制语句，但改写成Java语法。

#### If/Else语句

用Java语句编写上问的if/else：

```java
int x = 10;

if ( x > 5 ) {
    System.out.println("X is GREATER than 5!");
} else {
    System.out.println("X is NOT GREATER than 5!");
}
```

这里的`if`例子几乎和 JavaScript一样，唯二不同是我们声明了 _x_ 的数据类型为`int`以及我们使用了 `System.out.println()` 而不是 `console.log()`来打印消息。

接下来，我们将讨论 Java 中的循环。Java和JavaScript语法非常相似，所以Java中的`while`循环与我们在JavaScript中看到的基本相同：

```java
int x = 1;

while ( x <= 100 ) {

    System.out.println("This is a very important message!");
    
    x = x + 1;
    
}
```

这个`while`循环将打印出指定的消息100次。

我们介绍编程语言的部分到此结束。由于我们使用相同的概念集介绍3种语言，因此可能稍显重复，但希望这有助于为你打下坚实的基础。

接下来我将介绍一些其他相关话题，你不需要立刻就开始学习这些主题。

我们将讨论一个名为 Git 的重要协作工具，然后我们将学习在数据库中存储和访问数据。接下来我们将简要介绍Web开发框架，最后我们稍微了解包管理器。

<h2 id="11-track-your-code-using-git">11)使用Git跟踪代码</h2>

Git是在最流行的版本控制系统(VCS)。它允许多个开发人员一起协作开发软件。在本节中，我们将了解 Git 是什么、它是如何工作的以及如何操作它的基本命令。

在直接进入Git之前，让我们补充一些编程项目共有的概念。

一个软件项目的全部目录和文件被称为**代码库**。**项目根**是项目目录树中最高级别的文件夹。代码文件可以直接在项目根中，也可以被组织到多个级别的文件夹中。

当代码库准备好进行测试或部署时，它可以被**构建**成将在你的计算机上运行的程序。**构建过程**可以包括一个或多个步骤，这些步骤将人类编写的代码转换成可以被计算机处理芯片可执行的文件。

构建代码后，程序就可以在特定操作系统上运行，例如 Linux、Mac OS 或 Windows。

随着时间的推移，开发人员会更新项目代码以添加新功能、修复错误、实施安全更新等。一般来说，开发人员可以通过三种方式对软件项目更改：

1.  将新文件和文件夹添加到项目中
2.  编辑现有文件和文件夹中的代码
3.  删除现有文件和文件夹

随着项目的壮大和新功能的添加，文件和文件夹的数量（以及其中的代码量）也会增加。大型项目可以壮大到包含数百万行代码的数十万个文件。

为了支持这种增长，项目团队的开发人员数量通常会增加。大型软件项目可能有数百甚至数千名开发人员协同工作。

这就引出了问题： "_这些分布在世界各地的开发人员到底是如何跟踪他们的软件项目代码，以便他们可以在一个项目上一起工作？_"

开发团队需要准确跟踪对代码进行了哪些更改，哪些文件或文件夹受到了影响，以及是谁进行了每次更改。每个开发人员得能够获得其他开发人员的更新。

此过程称为**版本管理（versioning）**或**版本控制（version control）**。开发人员使用称为**版本控制系统** (VCS) 的特殊工具来跟踪、管理和共享软件项目的版本。以下是一些流行版本控制系统：

-   Git
-   Subversion (SVN)
-   Mercurial (Hg)

Git赢得了VCS的桂冠。迄今为止，它是被全球政府、商业和开源社区使用。

Git促成了基于Web的VCS平台（如 GitHub 和 Bitbucket）的流行。对于任何全面发展的开发人员来说，Git是一个必须要添加到技能包里必不可少的工具。

### 基本Git命令

Git在**Git仓库**中创建和存储有关我们软件项目的信息。Git仓库只是计算机上的一个隐藏文件夹，Git使用它来存储有关软件项目中代码文件的数据。

我们使用的每个软件项目通常都有自己的Git仓库，用于存储与该项目相关的信息。这样，可以单独跟踪与单个计算机上的不同项目相关的代码。

在计算机上创建Git仓库有两种主要方法。第一个是在文件系统的现有文件夹中创建一个全新的Git仓库。

只需打开命令行，在桌面创建一个新文件夹，然后进入：

```sh
cd ~/Desktop

mkdir testgit
 
cd testgit/
```

现在我们创建了一个新文件夹并进入它，我们可以使用以下命令初始化一个新的Git仓库：

```sh
git init
```

应该会看到类似于以下内容的输出：

```sh
Initialized empty Git repository in /Users/me/Desktop/testgit/.git/
```

我们要运行的所有Git命令都以`git`开头，接着一个空格，然后是我们要运行的具体Git命令。有时我们也会在Git命令后面添加标志和参数。

`git init`命令在当前目录下创建一个名为`.git`的隐藏文件夹。这个文件夹就是我们上面提到的Git仓库。你可以通过运行`ls -al`命令来查看。

获取Git仓库的第二种方法是从其他地方下载一个，例如Bitbucket或GitHub。

Bitbucket和Github是允许人们托管开源项目的网站，可以将项目下载到你的电脑。

如果你在Bitbucket或GitHub上浏览到一个你感兴趣的项目，你会看到一个标有Clone的按钮。这个按钮会给你提供一个命令和URL，你可以把它复制并粘贴到命令行终端：

```sh
git clone https://jacobstopak@bitbucket.org/jacobstopak/baby-git.git
```

`git clone`命令从指定的URL下载版本库到你电脑上的一个新文件夹。这个URL可以是上面例子中的网页URL，也可以是SSH URL，如下所示：

```sh
git clone git@bitbucket.org:jacobstopak/baby-git.git
```

运行`git clone`命令后，你应该会看到创建了一个新文件夹。如果浏览它，将看到你下载的项目的所有文件和子文件夹。

接下来我们要提到的命令是`git add <filename.ext>`。`git add`命令用来告诉Git我们想让它跟踪哪些文件，并把已经跟踪的文件的改动添加到 Git的**暂存区域**。

一旦新文件或更改的文件被暂存，就可以用`git commit -m "Commit message" 命令将它们提交到仓库。将在Git仓库中存储所有暂存文件的更改。

使用`git status`和`git log`命令可以查看工作目录的当前状态和项目的提交历史。

我们在这里只触及了表面，[Git还有很多必要的命令](https://initialcommit.com/blog/Git-Cheat-Sheet-Beginner) 值得我们去熟悉。

<h2 id="12-store-data-using-databases-and-sql">12)使用数据库和SQL来存储数据</h2>

数据库是专门用于有效存储、更新、检索和删除大量数据的程序。简而言之，我们可以把数据库看成是一组表格的容器。

你可能使用过Microsoft Excel中的表格。表只是一组包含数据的列和行。我们可以在数据库中设置表格来存储我们的程序正常工作所需的信息。

无论我们是用JavaScript、Python、Java还是其他语言编写程序，我们都可以根据需要，告诉我们的程序与数据库交互。

我们可以从数据库中检索数据，在网页上显示给我们的用户。我们可以接受一个用户的网络注册表，并将该用户的信息存储在数据库中供以后使用。

程序可以在运行时与数据库进行实时互动。要做到这一点，大多数数据库使用一种叫做**SQL**的语言，即**结构化查询语言**的简称。

SQL是一种专门为数据库创建的编程语言。可以通过SQL告诉数据库要做什么。

一段SQL代码称为**查询（query）**。我们可以编写SQL查询来获取我们在特定时间需要的数据，或者将新数据插入到特定的表中。粗略地说，有两种主要的SQL查询类型：**read-SQL** 和 **write-SQL**。

read-SQL是一种简单地从数据库中获取数据供我们查看或使用的查询。它完全不改变数据库中的数据。

write-SQL要么在表中插入新数据，要么更新现有数据，要么删除现有数据。我们将在本节中学习如何编写一些基本的read-SQL查询。

在编写查询之前，我们要知道我们编写的查询的是什么! 传统的数据库是由列和行组成的**表**。当我们写一个read-SQL查询时，我们的目标通常是检索这些行和列的一个子集。

例如，假设我们有一个名为`PERSON`的表，有4列，`FIRST_NAME`和`LAST_NAME`。我们可以使用下面的查询，只从`FIRST_NAME`列中选择所有数据。

```sql
SELECT FIRST_NAME FROM PERSON;
```

SELECT关键字告诉数据库我们要检索数据。后面接着我们想要查询的列名FIRST\_NAME。

然后我们使用FROM关键字告诉数据库要从哪个表中获取数据，在本例中为PERSON表。另外，请注意所有SQL命令都以分号结尾。

我们对数据最常见的要求之一是对其进行过滤。过滤意味着根据指定的条件来限制结果集。

例如，我们可能只想从`PERSON`表中选择名为"PHIL"的人的记录。我们可以使用`WHERE`关键字在SQL查询中应用过滤器。

```sql
SELECT * FROM PERSON WHERE FIRST_NAME = 'PHIL';
```

这个查询将返回`PERSON`表中的所有列，因为我们在`SELECT`子句中使用了星号`*`，而没有列出具体的列名。只有`PERSON`表中`FIRST_NAME`被设置为 "PHIL"的记录才会被检索出来。

最后，我们来谈谈排序问题。有很多时候，我们希望看到查询结果以特定的顺序进行排序。可以使用`ORDER BY`子句来实现这一点。

```sql
SELECT *
FROM PERSON
ORDER BY LAST_NAME;
```

这将返回`PERSON`表中的所有列，按姓氏的字母顺序排序。

默认情况下，结果将按升序排序，从A到Z。我们可以添加可选的`ASC`或`DESC`关键字，以指定是按升序还是降序排序。

```sql
SELECT *
FROM PERSON
ORDER BY LAST_NAME DESC;
```

<h2 id="13-read-about-web-frameworks-and-mvc"> 13)阅读Web框架和MVC</h2>

很多时候，我们是在为非常常见的应用程序类型编写代码。web应用程序（或称**web apps**）是依靠互联网来运作的应用程序。web应用程序便是最常见的软件应用程序类型之一。

web应用程序本质上是一个功能更强大的网站。大多数web应用程序实现了一些网络服务器上的后端代码，并在幕后执行逻辑，以支持应用程序的功能。

web应用程序后端代码使用的常见编程语言包括Python、Java和JavaScript等。

Web应用程序共有的一些功能包括：

-   提供一种方便的方式来动态更改网页上的内容
-   通过登录页面执行安全用户身份验证
-   提供强大的应用程序安全功能
-   读取和写入数据到数据库

Web框架是一组代码库，其中包含所有Web应用程序可以开箱即用的常用功能。 Web框架为开发人员提供了一个系统来构建他们的应用程序，使用框架就不必担心Web应用程序常见的许多幕后任务的编写代码。

我们只需要利用框架中满足Web应用程序需求的部分即可。

例如，如果我们不需要连接到特定Web应用程序中的数据库，我们可以忽略数据库功能并使用我们确实需要的其他功能。

我们可以定制应用程序的网页、用户流和业务逻辑。你可以把web框架看成是一个编程工具包，我们可以用它来构建web应用。

本文中所涉及的编程语言都有一个或多个流行web框架。它让开发团队可以灵活地使用他们最精通的语言的框架。

Java有Spring框架，通过**Spring Boot**使得开发变得方便。Python有**Django**框架。JavaScript有**Node.js**运行环境，包括**Express.js**和**Meteor.js**等多个框架选项。这些框架都是免费和开源的。

<h2 id="14-play-with-package-manager"> 14)玩转包管理工具</h2>

本指南的最后一个主题是**软件包管理器**。根据环境的不同，**包**可以代表一个准备安装在计算机上的独立程序，也可以代表一个我们想在某个软件项目中利用的外部代码库。

我们的应用程序经常依赖这些外部代码库，因此我们也将它们称为**依赖项**。

包管理器是帮助我们维护系统或软件项目的依赖项的程序。“维护”是指根据需要安装、更新、列出和卸载依赖项。

我们讨论的包管理器既可以用于维护我们在操作系统上安装的程序，也可以用于维护软件项目的依赖项。

### Mac OS X: Homebrew

**Homebrew**是Mac OS X操作系统上最流行的包管理器。它提供在Mac上安装、更新、跟踪、列出和卸载软件包和应用程序的便捷方式。

许多可以通过.dmg文件下载安装的应用程序也可以使用Homebrew下载和安装。

以下是通过Homebrew安装`wget`包的示例：

```sh
brew install wget
```

### Linux: Apt和Yum

Linux是围绕命令行构建的，包管理器是安装程序的默认方式也就不足为奇了。

大多数主流版本的Linux都带有内置的包管理器。**Advanced Package Tool**(APT)是Debian和基于Ubuntu的Linux发行版的本地包管理器。 **Yellowdog Updater, Modified** (YUM)是RedHat Linux发行版的本地包管理器。

下面是一个使用APT安装Vim的例子：

```sh
sudo apt-get install vim
```

And using Yum:

```sh
sudo yum install vim
```

### JavaScript: Node Package Manager (NPM)

现在我们已经了解了一些操作系统级别的包管理器是如何工作的，让我们来看看编程语言的包管理器。这些可以帮助我们管理项目所依赖的软件库。 **Node Package Manager (NPM)**默认随Node.js一起安装。

NPM与我们之前看到的包管理器之间的一个区别是NPM可以在**本地**或**全局**模式下运行。本地模式用于仅在我们正在处理的特定项目/目录中，而全局模式用于在系统上安装包。

默认情况下，软件包安装在本地，但您可以使用`-g`标志全局安装软件包：

```sh
npm install request -g
```

### Python: Pip

Python有一个名为**Pip**的包管理器。你的系统可能已经安装了Pip，因为它与最新版本的Python打包在一起。我们可以轻松地从**Python索引安装包**使用`pip install <package-name>`命令来安装Pip：

```sh
pip install requests
```

### Java: Apache Maven

**Apache Maven**（通常简称为** Maven**）是一个免费的开源工具套件，包括依赖管理。

尽管也支持其他语言，Maven主要用于Java项目。 Maven可以做很多事情。它的使用稍微复杂一些，我们在这里不再赘述。

## 总结

我在本文介绍了一些基本的编码概念和工具，旨在展示软件开发鸟瞰图，我希望我当初开始学习编程的时候也有这份鸟瞰图。

涵盖的主题包括互联网、几种编程语言、版本控制系统和数据库，我尝试描述这些拼图如何组合在一起的。

## 未来规划

如果你喜欢这篇文章，我写了一本名为[《面向开发人员的 Coding Essentials Guidebook》](https://initialcommit.com/store/coding-essentials-guidebook-for-developers)的书，一共14章，每章都涵盖了本文中讨论的一个主题。

在这本书中，我对这14个主题进行了更深入的研究，因此这本书是检验你是否从这篇文章有所收获的一个途径。

可能因为这篇文章被某种特定的语言、工具或概念所吸引，我鼓励您深入研究该领域以进一步学习。

如果你这本书有任何问题、建议或疑虑，我很乐意听取您的意见，你可以发邮件到[jacob@initialcommit.io](mailto:jacob@initialcommit.io)。
