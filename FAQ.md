# XJTUthesis的常见问题(FAQ) #



## 关于`xjtuthesis` ##

### `XJTUthesis` 是为谁提供的? ###

希望使用 LaTeX 完成学位论文的西安交通大学本科生, 硕士生和博士生.

### 谁开发了`XJTUthesis`? ###

[multiple1902](https://twitter.com/multiple1902), 西安交通大学计算机系的一位本科生.

### multiple1902写`XJTUthesis`是为了赚钱吗? ###

不是. 他的初衷是将成果分享, 确保每个人都能自由获得.

### LaTeX比Word到底好在哪? ###

太多了, 比如,  LaTeX 是开放和自由的, 并且简单易用, 方便并节约时间. Word 太烂了, 尤其是你在意排版效果的时候.

### 如何掌握LaTeX的用法? ###

熟能生巧.

## 开始使用`xjtuthesis` ##

### 如何得到`XJTUthesis`的源代码? ###

请点击项目主页的[Download标签](https://code.google.com/p/xjtuthesis/downloads/list). 通常最新发布的版本会出现在最上面.

把`xjtuthesis.cls`这个类文件和你的论文的主文件如`bachelor.tex`放在同一个目录下, 它就可以正常编译了. 当然, 你也可以用安装 LaTeX 宏包的一般方法, 把它安装到`texmf`目录下, 如果你知道怎么做的话.

### 如何升级`XJTUthesis`到最新版? ###

最简单的方法是用新的 `base/xjtuthesis.cls` 文件覆盖旧的同名文件. 此外, 你应当看看新版的示例中是否增加和修改了相关的命令(术语叫接口).

### 怎么才能迅速知道`XJTUthesis`发布新版? ###

方法很多哦:

  * 订阅[xjtuthesis在Google Groups的讨论组](https://groups.google.com/group/xjtuthesis),
  * 关注本项目的 [twitter 帐号](https://twitter.com/xjtuthesis) 或者[新浪微博帐号](http://weibo.com/xjtuthesis),
  * 关注兵马俑 BBS 的 [thesis 版面](http://bbs.xjtu.edu.cn/BMY/home?B=thesis),
  * 订阅本项目的 [Downloads](https://code.google.com/p/xjtuthesis/downloads/list) 列表.

### 我应该用哪个LaTeX发行版? ###

`XJTUthesis`是在TeXLive上开发的, 它使用`xeCJK`来实现中文支持. 推荐使用TeXLive发行版, 它可以从很多CTAN镜像下载到, 比如[这里](http://mirrors.ustc.edu.cn/CTAN/systems/texlive/Images/). 除非你知道你在做什么, 否则请不要使用CTeX或ChinaTeX这类"中国化"的发行版来完成编译.

### 为什么你对CTeX这么大的意见? ###

CTeX中的WinEdt(共享软件)是被破解过的. 可以一直用下去而不会被提示注册. 真的, 谁用谁丢人. 我想, 并不是别人偷来的东西就可以心安理得使用的吧.

### 大家不都用破解软件么? ###

滚.

### 为什么源代码里一堆乱码? ###

这说明您使用的源代码编辑器弱爆了. 别折磨自己了, 换一个靠谱点的吧, 比如[TeXMaker](http://www.xm1math.net/texmaker/), [TeXWorks](http://www.tug.org/texworks/).

### 如何反馈问题? 给multiple1902发邮件? ###

表这样. 如果你要反馈`xjtuthesis`的问题(issue), 请使用我们在Google Code的项目页面上的[Issue Tracker](https://code.google.com/p/xjtuthesis/issues/list).

### 我可以在issue tracker上发布不是反馈问题的帖子吗? ###

表这样. 不过你可以在[xjtuthesis在Google Groups的讨论组](https://groups.google.com/group/xjtuthesis)发表帖子.

### 错误信息里提到了`fontspec`, 是怎么回事? ###

请使用`xelatex`排版引擎而不是默认的`latex`, 通常可以在你的编辑器里找到这个选项.

## 加入`XJTUthesis` ##

### 我如何才能向`XJTUthesis`项目提供帮助? ###

各种形式的支持都很棒. 比如, 你可以提交补丁, 甚至成为项目开发者. 当然, 向你周围的人推荐 `xjtuthesis` 项目也是很重要的.

### 为什么不把`XJTUthesis`托管在GitHub或者BitBucket上? ###

出于一些原因, 我希望`xjtuthesis`成为一个没有歧义的项目名称. fork 将会破坏副本的一致性. 如果你想向 `xjtuthesis` 项目作出贡献, 欢迎成为一名开发者(committer).