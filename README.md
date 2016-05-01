Punch & Kick
================

这是一个和《热血格斗》大致一样的格斗游戏，游戏名称暂命为：Punch & Kick，如果你有兴趣，可以为此游戏取一个高端大气上档次的名字，或者低调奢华有内涵的名字也可以。

此游戏由作者利用闲于时间开发，其开发目的主要为了实现作者自己的想法，为了让作者的大学时间不被浪费，也是为了方便作者以后找工作。

源代码基于 GNU通用公共许可协议第二版(GPLv2) 发布，作者之所以开源，主要是为了与其他开发者以及业余编程爱好者们进行技术交流，顺便满足作者的展现欲。

此游戏主要是依据作者个人的想法进行开发的，作者并未想要将它做成符合大众口味的游戏，请不要期望这款游戏能够符合你的口味。

由于作者以后工作的原因，此游戏的开发可能会暂停，因此，请不要对此游戏抱有过多的期待。

## 效果图
![screenshort 1](https://blog.lc-soft.io/static/images/game/2013-11-15-21-54-36.png)
![screenshort 2](https://blog.lc-soft.io/static/images/game/2013-11-15-22-02-07.png)

## 构建

在 GNU/Linux 平台上，请先确认你已经安装了 LCUI 库，然后在游戏源码根目录中使用命令：

```shell
	./configure
	make
```

生成的游戏主程序会在src目录里，名为game，请将它移动至bin目录下，若要运行游戏，请
先进入字符控制台模式，以确保能够正常显示图形。

在 windows 平台上，你需要准备VisualStudio，2010或2012版都行，进入build目录中的相应
目录，打开sln文件，然后用VisualStudio生成即可，生成的可执行文件在bin目录下。

如果你使用的是其它开发工具，请根据该开发工具的用法手动创建一个工程，并把游戏的源文件及头文件添加进工程里，然后将include和bin目录分别添加至头文件目录和库目录。

## 代码阅读

头文件及源文件所使用的字符编码主要是UTF-8，并且带BOM签名，请确保你的代码编辑器支持显示UTF-8编码的文本内容。

源代码的缩进宽度为8，请确保你已经将你的代码编辑器的缩进宽度设置为8，这样，代码才能够以应有的格式显示，方便阅读。

请将代码编辑器所使用的字体更改为等宽字体，以让显示的代码具有良好的视觉效果。

本项目的源代码中的注释不是很多，建议使用自带代码提示功能（例如：提示函数原型及对应的注释）的代码编辑器查看，帮助理解部分代码。

![vs2012 code hints feature](https://blog.lc-soft.io/static/images/vs2012-code-hints-feature.png)
