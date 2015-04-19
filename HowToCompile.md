# 准备工作 #

  * 确保你已经安装了一个靠谱的LaTeX发行版, 比如[TeXLive](http://www.tug.org/texlive/). CTeX当然也行...就是不太好啦. 我们主要是用到里面的`xelatex`程序.
  * 字体方面, 你通过解除对`truefont`一行的注释来使用SimSun(中易宋体)和Times New Roman字体. `truefont`一行被注释时, 文档默认会使用文鼎ＰＬ简报宋和Nimbus Roman No9 L这两款字体. Windows用户通常会解除注释`truefont`一行, 因为他们的电脑里通常安装了SimSun和Times New Roman字体. 解除注释也就是把这行开头的百分号删掉. **因为无视本行说明而导致的编译错误, 作者将不予解释.**
  * 如果你没有把`xjtuthesis.cls`复制到你的`texmf`路径下, 那就得把它放到你要编译的`.tex`文件所在的位置. (看不懂的话就照着做)

# 在图形界面下编译 #

用你的LaTeX编辑器打开你要编译的`.tex`文件, 如果可能, 选择使用`xelatex`模式, 然后点击"编译".

在不同的编辑器上, 操作步骤会有所不同. 编辑器方面, 你的选择太丰富了, 我们很难给出一个统一的指导.

注意, 很多LaTeX编辑器默认使用`latex`命令编译, 而不是`xelatex`. 如果你看到关于`fontspec`包的报错, 很可能你应该改用`xelatex`.

# 在命令行中编译 #

比如, 我们要编译的文件是`bachelor.tex`. 执行以下命令:
  1. `xelatex -no-pdf --interaction=nonstopmode bachelor.tex`
  1. `bibtex bachelor`
  1. `xelatex -no-pdf --interaction=nonstopmode bachelor.tex`
  1. `xelatex --interaction=nonstopmode bachelor.tex`

不出意外的话, PDF文件应该已经生成了. ~~未来的版本中我将会提供自动化的脚本.~~