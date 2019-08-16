>* 文章作者：[Wendell](https://www.jianshu.com/u/8532ed726e58)
>* [原文地址](https://www.jianshu.com/p/a152f82c5e4a)：https://www.jianshu.com/p/a152f82c5e4a
>* 转载请注明出处！
___
##一、安装前准备
&emsp;&emsp;1. [廖雪峰老师Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) ：推荐Git入门教程。
&emsp;&emsp;2. 按照自己的系统版本下载Git软件，我的操作系统：Windows7  64位，安装版本为Git-2.18.0-64-bit.exe（截至2018.8.27最新版本）。
&emsp;&emsp;[Git下载地址](https://git-scm.com/download/win)：国外网站，可确保为最新版本。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-543050ebb9110954.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;[百度网盘下载](https://pan.baidu.com/s/194uzbJ9vB5lgi_TbxhRE1Q)：国内镜像，如果网速慢可以到网盘下载。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-67c174906f129cd1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##二、安装过程
&emsp;&emsp;1. 下载完成后，双击下载好的软件开始安装，出现如下对话框
![image.png](https://upload-images.jianshu.io/upload_images/13946060-886d45795bc9b13a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;2. 点击Next，默认选项和图中不一样，建议按照图中修改，Git Bash Here和Git GUI Here可以方便的在任意目录下打开git，建议选中，选中这两项后Additional icons->On the Desktop就按照自己心情了。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-c73d19ea1b7f0f38.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;**这一步根据自己需要设置后，不爱折腾的小伙伴下面的步骤可以直接采用默认选项，当然也可以详细研究选择最适合自己的。**

&emsp;&emsp;3. 点击next,选择默认编辑器，我选择的是Notepad++。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-8677c12ab39a0040.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;4. 继续next,配置PATH环境。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-4351c7337ab39a31.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;Use Git from Git Bash only：这是最安全的选择，因为你的PATH根本不会被修改，你只能使用Git Bash的Git命令行工具。
&emsp;&emsp;Use Git from the Windows Command Prompt：这个选项被认为是安全的，它只向PATH添加一些最小的Git包，以避免使用可选的Unix工具混淆环境。你将能够从Git Bash和Windows命令提示符中使用Git。建议选择此项。
&emsp;&emsp;Use Git and optional Unix tools from the Windows Command Prompt：Git和可选的Unix工具都将添加到计算机的PATH中。警告：这将覆盖Windows工具，如“find”和“sort”，只有在了解其含义后才使用此选项。

&emsp;&emsp;5. 继续next，**以下选项均为默认**。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-77d21c0fa3361c3c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/13946060-74e1e5311069129e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/13946060-b1acf901971af6c6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/13946060-5fbe30c4a507eb30.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;点击Inall开始安装，安装完成后点击Finish即可。
&emsp;&emsp;在开始菜单里点击“Git“Git Bash”，弹出类似命令行的窗口，就说明Git安装成功！
&emsp;&emsp;在任意目录下右击，可以看到右键菜单中有Git GUI Here和Git Bash Here两个选项。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-aae816f4adbf6c9d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##三、安装后的设置
&emsp;&emsp;安装完成后需要设置自己的git账号和邮箱，否则无法正确使用，但是到目前为止还没有申请git账号，下面就来说一下具体的账号申请和git设置过程。点击[账号申请网址](https://github.com/) ，出现如下界面。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-5a76430ec6bc2dc4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;输入自己想要的账户名，自己的邮箱和密码，账户名只能包含字母和数字字符或者是单个连字符“-”并且连字符不可以作为开头或者结尾；密码中至少包含一个字母，一个数字，并且长度不小于7个字符。输入完成后后点击“Sign up for Github”，进入如下界面，同时注册用的邮箱中会收到一封GitHub的邮件。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-049bd73537d9248a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;通过验证后点击“Create an account”

![image.png](https://upload-images.jianshu.io/upload_images/13946060-703e475d51aa9dce.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;如果不需要保密，选择默认的免费选项即可，如果需要保密则需要付费。
&emsp;&emsp;点击Continue，出现无关紧要的答题，选选就好，之后Submit，搞定。
![image.png](https://upload-images.jianshu.io/upload_images/13946060-335f6531ff90a0af.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;因为Git是分布式版本控制系统，所以，每个机器都必须自报家门：你的名字和Email地址。账号申请完成后，打开命令行或者Git Bash，输入
&emsp;&emsp;git config --global user.name "Your Name"，之后回车，再输入
&emsp;&emsp;git config --global user.email email@example.com
&emsp;&emsp;其中Your Name和email@example.com替换成上面注册时的账户名和邮箱。
&emsp;&emsp;命令行下输入和Git Bash下输入均可。
&emsp;&emsp;命令行下输入如图：
![image.png](https://upload-images.jianshu.io/upload_images/13946060-5a6d06242c074f72.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;Git Bash下输入如图：
![image.png](https://upload-images.jianshu.io/upload_images/13946060-311298d4ead4779e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
&emsp;&emsp;到这一步，Git的安装设置就基本结束了，可以在本机正常使用了，如果需要使用其他功能，请参考[廖雪峰老师Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) ，已经讲解的很详细了，不再赘述。

















