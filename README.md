# 阅读笔记
个人阅读笔记，仅供参考。
日历即将翻到新的一页，每个人都有权利在此刻擦去身上的浮沉，点燃新年的梦想。祝大家新年快乐！

### 目录
*   [把时间当作朋友](#getting-timefriend)
*   [Git快速入门](#getting-gitstarted)
*   [时间管理工具](#getting-rescuetime)
*   [代码整洁之道](#getting-cleancode)
*   [微信小程序](#getting-weixinapp)


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
2017年第一天继续自己的阅读计划，2017年第一本书。


# <a name="getting-cleancode"></a>微信小程序
微信小程序正式上线 能把手机应用都收到微信里去吗？
http://news.163.com/17/0109/19/CAC4PLU100018AOQ.html


