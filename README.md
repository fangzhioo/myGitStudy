# myGitStudy

用来学习git的相关内容的项目，一边用来学习git，一边用来记录自己的学习。（我是个新手！有问题请指出，大家一起学习！歇歇~）

## 关于git
 Git 是 Linux 发明者 Linus 开发的一款新时代的版本控制系统

 这是来自官方网站的介绍
>Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

>Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

 按照我的理解，git就是一个分布式的版本控制器，说白了，就是用来记录和贮存版本变化的系统。对于代码开发来说，是一个非常重要的、也是非常有必要学习的一个工具。

 比如，再写一段代码的时候，需要添加一个新的功能模块。如果按照以前的方式，就是直接在原版本上修改，一旦出现问题，需要退回到功能之前的版本，就很麻烦了。但是用git可以在添加新的功能模块之前，创建一条分支，在分支上修改、添加新的代码。等完全测试通过了，在合并到主分支上即可。

 同样的，可以用来多人协同开发同一个项目，只需要fork一下主仓库的代码。拉取到本地，就可以各自完成各自的工作了，当完成之后，提交到远程，由管理员审核通过后，就合并到主仓库了。

 当然，git能做的事情远远不止这些，当然也有一些骚操作了，这个妹子的回答就很厉害。
* [怎样使用GitHub？](https://www.zhihu.com/question/20070065/answer/79557687)

## 安装git
 Git 是一个版本控制系统，也可以理解成是一个工具，跟 Java 类似，使用之前必须得先下载安装，所以第一步必须要安装。
- Mac：[git-osx-installer download](git-osx-installer download)
- Windows：[Git for Windows](Git for Windows)
- Linux：Debian系列：apt-get install git
        Fedora上：yum install git-core

