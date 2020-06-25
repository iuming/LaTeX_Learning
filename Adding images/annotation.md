# 注解
```
\graphicspath{ {images/} }
```
LaTex本身不能管理图像，所以你需要使用一个包。包可以用来改变你的默认外观LaTex文件，或允许更多的功能。在这种情况下，您需要在我们的文档中包含一个图像，因此您应该使用该graphicx软件包。该软件包提供了新命令，\includegraphics{...}和\graphicspath{...}。要使用该graphicx程序包，请在序言中包含以下行：\usepackage{graphicx}        

该命令\graphicspath{ {images/} }告诉LaTex，该图像被保持在文件夹中命名图像在当前目录下。      

```
\includegraphics{universe}
```
该\includegraphics{universe}命令是实际上将图像包含在文档中的命令。在这里，Universe是包含不带扩展名的图像的文件的名称，然后universe.jpg成为universe。图像的文件名不应包含空格或多个点。        

注意：允许包含文件扩展名，但是最好忽略它。如果省略文件扩展名，它将提示LaTeX搜索所有支持的格式。在上传图片文件时，通常也建议使用小写字母作为文件扩展名。    