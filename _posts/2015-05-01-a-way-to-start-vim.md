---
layout: post
title: "开始使用Vim"
description: "VIM使用入门，入门教程"
category: VIM
tags: [VIM, tutorial]
---

###Brief Introduction
VIM作为一款Linux下必备的编辑器，会使用的人都说好用，于是我在Windows上也装上了Gvim来尝试一下这个万能的编辑器呢。不得不说VIM的入门实在是太困难了。当然如果只是简单的使用插入功能，i，进入插入模式，直接敲，敲完ESC退出，再`:wq`保存退出，也就是最基本的入门了。当时如果想要尝试其他的功能，就不得不看文档，装插件，装配色方案，写VIMRC配置等等了。

其实很多VIMer都会对新手说一句看帮助文档，这句话对新手真的毫无用处，或许真的只有对VIM有了一定了解才能在文档的帮助下学到VIM更多的东西。文档一般都是大而全，有很多部分其实完全没有必要再新手阶段的时候就全部读完，而甚至有些命令，设置用了多年的VIMer都不会去接触一下。所以如何入门？首先要了解作为一个编辑器最基本的功能，写入，删除，修改，保存，编码，而对于VIM，还有几大模式，移动光标，替换操作等等。

###vimtutor
在最短的时间内了解这个编辑器的简单功能，至少把他能够当成一个编辑器使，再不济能够直接使用键盘来浏览文件内容，对文件内容进行修改，删除，保存。当然在几十分钟内你可能要记住几十个命令，以及每个命令对应的操作。可能这对于很多新手来说需要锻炼一段时间才能记住，所以不要怕，用记事本，或者VIM记下来每个命令和对应的功能，之后不断的练习，很短的时间就能习惯这种操作。在习惯了之后就会发现再移动鼠标是多么的慢。当然你可能在VIM默认配置中有很多不太习惯的地方，把你那些不习惯记住，把那些你想要的功能一个一个记下来，在以后的学习中，我们来一一解决。
比如我在最初的时候觉得j/k在行之间移动，有些时候中文一行比较长，显示的时候跳跃了很多行，而是用j/k移动光标的时候在几行之间跳跃，让我很不习惯，当然这个在之后的学习中偶然看到了原来只要在VIMRC中配置`<map> j gj`就能够用j来直接到下一行，即使这一行事实上是VIM中的一行。还有很多很多的问题，都在短短几天的时间内一一得到了解决。所以开始的时候用极短的时间略读一遍vimtutor先熟悉。哦，对了，vimtutor在哪里，Windows下是在VIM安装目录下`vimtutor.bat`这个文件，双击运行，而Linux下直接终端运行vimtutor即可。当然这一切都在VIM的帮助文档中写着了，你可以尝试在VIM普通模式下运行`:help vimtutor`VIM会把文档全部显示出来。

###vimrc
在熟悉了最基本的命令之后，你可以开始看文档，尝试修改vimrc配置，当然如果你不想看英文文档，VIM还是有[中文文档](http://vimcdoc.sourceforge.net/)的。不想覆盖`:help `的文档，直接下一个PDF的随时查看也挺好，在熟悉了一下命令之后，直接看英文的也就很快了。我的方法就是直接看别人的配置，去Github上面一搜，很多人把自己的配置都公开了，就去一条条试试那些命令，有什么作用，我自己能怎么修改，然后查文档，很快你自己熟悉的配置就有了。

###Plugin
当然在熟悉VIMRC配置之后，在随便哪个文件中只要运行`:edit $MYVIMRC`就能够直接编辑vimrc文件，我在网上看别人的博客，于是我也就用了很多人推荐的Vundle来管理我的插件，从此之后再不用下载，解压，复制，只需要修改vimrc配置就能够安装插件，同样也只要保存一份配置文件就能够同步我的插件，这件事简直太棒了。当然最初安装Vundle这件事情是要你自己来的。直接去Vundle主页看吧。

###colorscheme
或许在练习了VIM不久就会觉得VIM的颜色太单调，但是没关系，VIM有很多很多的配色方案，只要你能找到总能找到自己喜欢的，我直接用了别人推荐的[molokai](https://github.com/tomasr/molokai),你也可以试试，下载molokai.vim文件到colors目录下之后，在vimrc中写入`colorscheme molokai`，就能使用这款配色了。当然你也能自己定义字体和字号，还有很多你能自己定义的东西等待发掘的。

附送两张图
![vi tutorial](https://lh5.googleusercontent.com/-Ox74nXfnQ0s/VUZBTBRQjjI/AAAAAAAAnjk/yw6e1DG7AWA/s0/vi_tutorial.png)

![vi key command](https://lh5.googleusercontent.com/-777zNXGtePg/VUSf2KO3eoI/AAAAAAAAnjM/zrkNBCUya0o/s0/gVim_commond_tree.png)