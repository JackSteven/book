# 阅读笔记
个人阅读笔记，仅供参考。
日历即将翻到新的一页，每个人都有权利在此刻擦去身上的浮沉，点燃新年的梦想。祝大家新年快乐！

### 目录
*   [把时间当作朋友](#getting-timefriend)
*   [Git快速入门](#getting-gitstarted)
*   [时间管理工具](#getting-rescuetime)
*   [代码整洁之道](#getting-cleancode)
*   [微信小程序](#getting-weixinapp)
*   [双11电子书_不一样的技术创新_完整版](#getting-11)


#####  

# <a name="getting-timefriend"></a>把时间当作朋友
书  名 | 阅读笔记
----|----
《把时间当作朋友》| <https://github.com/JackSteven/book/blob/master/《把时间当作朋友》.md>

#####  

# <a name="getting-gitstarted"></a>Git快速入门
## Git 创建仓库
git init
Git 使用 git init 命令来初始化一个 Git 仓库，Git 的很多命令都需要在 Git 的仓库中运行，所以 git init 是使用 Git 的第一个命令。
在执行完成 git init 命令后，Git 仓库会生成一个 .git 目录，该目录包含了资源的所有元数据，其他的项目目录保持不变（不像 SVN 会在每个子目录生成 .svn 目录，Git 只在仓库的根目录生成 .git 目录）。
使用方法
使用当前目录作为Git仓库，我们只需使它初始化。 
```
git init
```
该命令执行完后会在当前目录生成一个 .git 目录。
使用我们指定目录作为Git仓库。 
```
git init newrepo
```
初始化后，会在 newrepo 目录下会出现一个名为 .git 的目录，所有 Git 需要的数据和资源都存放在这个目录中。
如果当前目录下有几个文件想要纳入版本控制，需要先用 git add 命令告诉 Git 开始对这些文件进行跟踪，然后提交： 
```
$ git add *.c
$ git add README
$ git commit -m '初始化项目版本'
```
以上命令将目录下以 .c 结尾及 README 文件提交到仓库中。

https://github.com/937447974/Blog/tree/master/Git


# <a name="getting-rescuetime"></a>时间管理工具
[时间管理工具](https://www.rescuetime.com/)


# <a name="getting-cleancode"></a>代码整洁之道
2017年第一天继续自己的阅读计划，2017年第一本书。最近忙着发版本，没空上来更新读后感，糟糕的代码可以毁掉一家公司，听起来是不是很可怕。

童子军规：光把代码写好还不够，必须时刻保持代码整洁。我们都是见过代码随着时间流逝而腐败，我们应该更积极的阻止腐败的发生。


有意义的命名：选个好名字可能要花时间，但省下来的时间比花的时间多。注意命名，一旦发现有更好的名字，就换掉它。这么做，读你代码的人可能会很开心。

第三章 函数
函数：函数的第一规则是短小，第二规则还是短小。每个系统都是使用某种领域语言搭建，而这种语言是程序员设计来描述那个系统的。

函数是语言的动词，类是名词。这并非是退回到那种认为需求文档中的名词和动词就是系统中类和函数的最初设想的可怕的旧观念。其实这是个历史更久的真理。编程艺术是且一直就是语言设计的艺术。

大师级程序员把系统当作故事来讲，而不是当作程序来写。他们使用选定编程语言提供的工具构建一种更为丰富且更具表达力的语言，用来讲那个故事。那种领域定语言的一个部分，就是描述在系统中发生的各种行为的函数层级。在一种狡猾的递归操作中，这些行为使用它们定义的与领域紧密相关的语言讲述自己那个小故事。

本章所讲述的是有关编写良好函数的机制。如果你遵循这些规则，函数就会短小，有个好名字，而且被很好的归置。不过永远别忘记，真正的目标在于讲述系统的故事，而你编写的函数必须干净利落地拼装到一起，形成一种精确而清晰的语言，帮助你讲故事。

第四章 注释

注释的恰当用法是弥补我们在用代码表达意图时遭遇的失败。主意，我用了“失败”一词。注释总是一种失败。我们总无法找到不用注释就能表达自我的方法，所以总要有注释，这并不值得庆贺。

我为什么要极力贬低注释，因为注释会撒谎。也不是说总是如此或有意如此，但出现得实在太频繁。注释存在的时间越久，就离其所描述的代码越远，越来越变得全然错误。原因很简单，程序员不能坚持维护注释。


继续阅读

继续阅读

继续阅读



# <a name="getting-cleancode"></a>微信小程序
微信小程序正式上线 能把手机应用都收到微信里去吗？


http://news.163.com/17/0109/19/CAC4PLU100018AOQ.html

http://tech.qq.com/a/20170109/000599.htm



# <a name="getting-11"></a>双11电子书_不一样的技术创新_完整版_Final_1484734151317.pdf

一 ：硬件系统涉及领域众多，相互依赖度复杂，研发及测试周期长，投入资源与 产出效果存在显著滞后性。这些客观工程规律决定了基础设施层竞争力构建是一 项长期、艰苦、技术密集的过程。同时面对技术快速发展的外部产业环境和集团 业务与时俱进的内生需求迭代，主观上要求基础设施技术团队要沉淀出终身学习、 不断反思、不断求变的意识定位和心态。
笃定客户价值和长期技术竞争力构建的初心，阿里巴巴基础设施技术团队承 诺不断挑战自我、勇于创新、持续交付便捷高效优质的硬件基础设施解决方案。

继续阅读


