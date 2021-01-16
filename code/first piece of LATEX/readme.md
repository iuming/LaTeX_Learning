# 注解
```
\documentclass{article}
```
代码的第一行声明了文档的类型，称为类。 该类控制文档的整体外观。 不同类型的文档将需要不同的类别，即简历/简历与科学论文相比将需要不同的类别。 在这种情况下，该类是article，是最简单和最常见的LATEX类。 您可能正在处理的其他类型的文档可能需要不同的类，例如书籍或报道。            
```
\begin{document}
First document. This is a simple example, with no 
extra parameters or packages included.
\end{document}
```
之后，将写在\begin {document}和\end {document}标记内的文档内容写入。 这就是文档的主体。 您可以在此处开始编写，并根据需要更改文本。 要在PDF中查看这些更改的结果，必须编译文档。           
如果使用的是基本文本编辑器，例如gedit，emacs，vim，sublime，notepad等，则必须手动编译文档。 为此，只需在计算机终端/命令行中运行pdflatex <您的文档>。 