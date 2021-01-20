一、shell和c语言的区别:

```
shell是个脚本语言，也是应用程序与内核进行交互的桥梁（一个让开发者与内核交互的软件）。

比如我们计算机的运行状态等我们是无法肉眼来查看的，但是通过shell我们就能看到他的数据，其他一些应用程序，比如浏览器、音乐播放器等获得内核所掌管的音频、显卡等驱动的帮助。

shell也是个脚本语言，我们可以将一系列的操作放入一个文件中，并给予这个文件可执行的权限，我们就可以一下运行文件中的所有的指令，比如我们有一系列的操作经常使用，但是一个一个的打是在太麻烦了，我们可以将他写到一个脚本中，只需一次运行所有的操作就完成了。

而C语言是另一种高级的计算机语言，他可以开发很多软件，其实shell也是用c写的。
二、什么是脚本语言
```

脚本语言（Script languages,scripting programming languages,scripting languages）是为了缩短传统的编写-编译-链接-运行（edit-compile-link-run）过程而创建的计算机编程语言。此命名起源于一个脚本“screenplay”，每次运行都会使对话框逐字重复。早期的脚本语言经常被称为批处理语言或工作控制语言。一个脚本通常是解释运行而非编译。虽然许多脚本语言都超越了计算机简单任务自动化的领域，成熟到可以编写精巧的程序，但仍然还是被称为脚本。几乎所有计算机系统的各个层次都有一种脚本语言。包括操作系统层，如计算机游戏，网络应用程序，文字处理文档，网络软件等。在许多方面，高级编程语言和脚本语言之间互相交叉，二者之间没有明确的界限。一个脚本可以使得本来要用键盘进行的相互式操作自动化。一个Shell脚本主要由原本需要在命令行输入的命令组成，或在一个文本编辑器中，用户可以使用脚本来把一些常用的操作组合成一组序列。主要用来书写这种脚本的语言叫做脚本语言。很多脚本语言实际上已经超过简单的用户命令序列的指令，还可以编写更复杂的程序。

### 简介

脚本语言是为了缩短传统的 [编写](http://baike.baidu.com/view/787741.htm)- [编译](http://baike.baidu.com/view/69568.htm)- [链接](http://baike.baidu.com/view/147669.htm)- [运行](http://baike.baidu.com/view/1026025.htm)（edit-compile-link-run）过程而创建的计算机 [编程](http://baike.baidu.com/view/3281.htm)语言。 [1] 它的命名起源于一个脚本“screenplay”，每次运行都会使 [对话框](http://baike.baidu.com/view/119316.htm)逐字重复。早期的脚本语言经常被称为批量处理语言或工作控制语言。 [2]

一个脚本通常是解释运行而非编译。脚本语言通常都有简单、易学、易用的特性，目的就是希望能让 [程序员](http://baike.baidu.com/view/39175.htm)快速完成 [程序](http://baike.baidu.com/view/17674.htm)的编写工作。而宏语言则可视为脚本语言的 [分支](http://baike.baidu.com/view/493737.htm)，两者也有实质上的相同之处。 [3]

（概述图片来源： [4] ）

### 特点

1、脚本语言(JavaScript， [VBscript](http://baike.baidu.com/view/24920.htm)等)介于 [HTML](http://baike.baidu.com/view/692.htm)和C,C++,Java,C#等编程语言之间。　HTML通常用于格式化和链接文本。而编程语言通常用于向机器发出一系列复杂的指令。

2、脚本语言与 [编程语言](http://baike.baidu.com/view/552871.htm)也有很多相似地方，其 [函数](http://baike.baidu.com/view/15061.htm)与编程语言比较相像一些,其也涉及到变量。与编程语言之间最大的区别是编程语言的语法和规则更为严格和复杂一些.

3、与程序代码的关系：脚本也是一种语言，其同样由程序代码组成。

注：脚本语言一般都有相应的 [脚本引擎](http://baike.baidu.com/view/1743372.htm)来解释执行。 他们一般需要 [解释器](http://baike.baidu.com/view/592974.htm)才能运行。 [Python](http://baike.baidu.com/view/21087.htm)、JAVASCRIPT,ASP,PHP,PERL, [Nuva](http://baike.baidu.com/view/459695.htm)都是脚本语言。C/C++编译、链接后，可形成独立执行的exe文件。

4、脚本语言是一种解释性的语言,例如 [Python](http://baike.baidu.com/view/21087.htm)、vbscript,javascript,installshield script,ActionScript等等,它不象c\c++等可以编译成二进制代码,以 [可执行文件](http://baike.baidu.com/view/159830.htm)的形式存在，脚本语言不需要编译，可以直接用，由解释器来负责解释。

5、脚本语言一般都是以 [文本](http://baike.baidu.com/view/300107.htm)形式存在,类似于一种 [命令](http://baike.baidu.com/view/446604.htm)。

举个例子说：如果建立了一个程序,叫aaa.exe，可以打开.aa为扩展名的文件，为.aa文件的编写指定了一套规则(语法)，当别人编写了.aa文件后，自己的程序用这种规则来理解编写人的意图，并作出回应，那么，这一套规则就是脚本语言。 [5]

6、相对于编译型计算机编程语言：用脚本语言开发的程序在执行时，由其所对应的解释器（或称虚拟机）解释执行。系统程序设计语言是被预先编译成机器语言而执行的。脚本语言的主要特征是：程序代码即是脚本程序，亦是最终 [可执行文件](http://baike.baidu.com/view/159830.htm)。脚本语言可分为 [独立型](http://baike.baidu.com/view/988503.htm)和 [嵌入](http://baike.baidu.com/view/732561.htm)型，独立型脚本语言在其执行时完全依赖于解释器，而嵌入型脚本语言通常在编程语言中（如 [C](http://baike.baidu.com/view/10075.htm)， [C++](http://baike.baidu.com/view/824.htm)， [VB](http://baike.baidu.com/view/3063.htm)， [Java](http://baike.baidu.com/view/29.htm)等）被 [嵌入](http://baike.baidu.com/view/732561.htm)使用。 [1] [6]

7、和系统程序设计语言相比：不同是脚本语言是被解释而系统程序设计语言是被编译。被解释的语言由于没有编译时间而提供快速的转换，通过允许用户运行时编写应用程序，而不需要耗时的编译/打包过程。解释器使应用程序更加灵活，脚本语言的代码能够被实时生成和执行。脚本语言通常都有简单、易学、易用的特性，目的就是希望能让程序设计师快速完成程序的编写工作。 [1]

## [编辑本段](http://baike.baidu.com/link?url=Aaq402wmW4D4_f1LuG_xjZevLgHNviv_1ZpDwuFXQdqaGYETPHf7EVxdONKYpO35)脚本语言的优缺点

### 优点

快速开发：脚本语言极大地简化了“ [开发](http://baike.baidu.com/view/522596.htm)、 [部署](http://baike.baidu.com/view/388088.htm)、 [测试](http://baike.baidu.com/view/1619.htm)和 [调试](http://baike.baidu.com/view/322913.htm)”的周期过程。

容易部署：大多数脚本语言都能够随时部署，而不需要耗时的编译/打包过程。

同已有技术的集成：脚本语言被Java或者 [COM](http://baike.baidu.com/view/25941.htm)这样的组件技术所包围，因此能够有效地利用代码。

易学易用：很多脚本语言的技术要求通常要低一些，因此能够更容易地找到大量合适的技术人员。

动态代码：脚本语言的代码能够被实时生成和执行，这是一项高级特性，在某些应用程序里（例如JavaScript里的动态类型）是很有用也是必需的。 [7]

**缺点**

脚本语言不够全面：它们会要求一门“真正的”编程语言的存在，必须找一个数据库驱动程序将其内置进脚本语言里。

脚本语言并不是软件工程和构建代码结构的最佳选择，例如面向对象和基于 [组](http://baike.baidu.com/view/188545.htm)件的开发。

脚本语言通常不是“ [通用](http://baike.baidu.com/view/29797.htm)”语言，但是能够根据 [专门](http://baike.baidu.com/view/1221216.htm)的应用来调整，例如： [PHP](http://baike.baidu.com/view/99.htm)和 [万维网](http://baike.baidu.com/view/7833.htm)。 [7]

## [编辑本段](http://baike.baidu.com/link?url=Aaq402wmW4D4_f1LuG_xjZevLgHNviv_1ZpDwuFXQdqaGYETPHf7EVxdONKYpO35)脚本语言的应用和发展

### 一、应运

(1)：作为批次处理语言或工作控制语言。许多脚本语言用来执行一次性任务，尤其是 [系统管理](http://baike.baidu.com/view/635537.htm)方面。DOS， [Windows](http://baike.baidu.com/view/4821.htm)的 [批处理](http://baike.baidu.com/view/80110.htm)文件和 [Unix](http://baike.baidu.com/view/8095.htm)的 [shell](http://baike.baidu.com/view/849.htm)脚本都属于这种应用；

(2)：作为通用的编程语言存在，如 [Perl](http://baike.baidu.com/view/46614.htm)、 [Python](http://baike.baidu.com/view/21087.htm)、 [Ruby](http://baike.baidu.com/view/45135.htm)等。由于“解释执行， [内存管理](http://baike.baidu.com/view/4541016.htm)，动态”等特性，它们仍被称为脚本语言。但它们已经用于应用程序编写，用户也不把它们看作脚本语言；

(3)：许多大型的应用 [程序](http://baike.baidu.com/view/17674.htm)都包括根据 [用户](http://baike.baidu.com/view/200012.htm)需求而定制的惯用脚本语言。同样地，许多电脑 [游戏](http://baike.baidu.com/view/2468.htm)系统使用一种自定义脚本语言来表现 [NPC](http://baike.baidu.com/view/704.htm)(Non-Player Character，Non-Playable Character，Non-Player Class)和游戏环境的预编程动作。此类语言通常是为一个单独的应用程序所设计，虽然它们貌似一些通用语言(如Quake C，Modeled After C)，但它们有自定义的功能；

(4)：网页中的嵌入式脚本语言。熟知的 [HTML](http://baike.baidu.com/view/692.htm)(Hyper Text Mark-up Language)即 [超文本标记语言](http://baike.baidu.com/view/383720.htm)，就是一种脚本语言，它的解释器就是 [浏览器](http://baike.baidu.com/view/7718.htm)。 [JavaScript](http://baike.baidu.com/view/16168.htm)直到现在仍然是网页 [浏览器](http://baike.baidu.com/view/7718.htm)内的主要编程语言，它的ECMAScript标准化保证了它成为流行的通用嵌入式脚本语言。另外，随着 [动态网页](http://baike.baidu.com/view/348756.htm)技术发展， [ASP](http://baike.baidu.com/view/2616.htm)、 [JSP](http://baike.baidu.com/view/3387.htm)、PHP等嵌入网页的脚本语言正被广泛使用，不过这些脚本要通过Web Server解释,而Html则被浏览器执行；

(5)：脚本语言在系统应用程序中嵌入使用，作为用户与系统的接口方式。在工业控制领域，PLC编程、组态软件的脚本语言是扩充组态 [系统](http://baike.baidu.com/view/25302.htm)功能的重要手段；在通信平台领域， [IVR](http://baike.baidu.com/view/13766.htm)(自动语音应答)流程编程；Office办公软件，提供的宏和VBA；其他应用软件如ER Studio提供的Basic MacroEditor，用户可以编写Sax Basic脚本操作ER图，生成Access库、导出Word文档等扩展功能。 [8]

### 二、发展情况

脚本技术得益于计算机 [硬件](http://baike.baidu.com/view/25278.htm)的加速发展。某些情况下甚至系统程序设计语言也不够有效，因此不得不用汇编编写应用程序。而今的机器比1980年的快100～500倍，且仍在以每18个月翻一番的速度增长。计算机性能快速提高，使计算机程序越来越复杂。因此，开发时间已远比运行时间紧迫。这时，脚本语言作为系统程序设计语言的补充，开始被主要的 [计算机](http://baike.baidu.com/view/3314.htm)平台所同时提供。 [编程语言](http://baike.baidu.com/view/552871.htm)已经由性能低下的硬件与执行效率之间的矛盾，转变为快速变化的市场需要与低效的开发工具之间的矛盾，所以脚本语言的发展在软件开发中有着必然的趋势。 [1]

## [编辑本段](http://baike.baidu.com/link?url=Aaq402wmW4D4_f1LuG_xjZevLgHNviv_1ZpDwuFXQdqaGYETPHf7EVxdONKYpO35)几种脚本介绍

这类的常见的有JavaScript、VBScript、Perl、PHP、Python、Ruby、Lua。

脚本语言的特点是语法简单，一般以文本形式保存，并且不需要编译成目标程序，在调用的时候直接解释。这可以当做是脚本语言的判断标准，比如说JavaScript，你只需要用记事本新建一个Html文件，在里面加上一段脚本就可以了，在浏览器打开Html文件时自然会调用JS脚本。 [9]