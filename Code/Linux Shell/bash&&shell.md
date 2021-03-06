# LINUX shell #
> ##shell简介##  

在linux中，管理整个计算机硬件的其实是操作系统的内核（kernel），内核是需要被保护的，因此我们需要使用shell来跟内核通信。此处我们说的shell为广义的shell，凡是跟操作系统通信的接口都可以称为shell。目前一般的linux系统使用的shell是bash，我们可以使用的shell有很多种，比如Sun默认的C Shell、K SHell、TCSH、Bourne Again SHell(简称bash)。我们可以通过查询`/etc/shells`文件来查询我们当前系统所支持的shell。

> ##在线帮助man&info##  

常见的帮助文件都在**/usr/share/doc**下  
**帮助文档级别**

|标号|含义|
|:--------:|:--------:|
|1|使用者在shell环境中可以操作的命令或可运行文件|
|2|系统核心可调用的函数与工具|
|3|一些常用的function与library，大部分为C的libc|
|4|装置文件的说明，通常在/dev下的文件|
|5|配置文件或者是某些文件的格式|
|6|游戏|
|7|惯例与协议等，例如Linux文件系统、网络协议、ASCII code等的说明|
|8|系统管理员可用的管理命令|
|9|跟kernel有关的文件|

**帮助文档内容**

|标号|含义|
|:--------:|:--------:|
|NAME|简短的命令、数据名称说明|
|SYNOPSIS|简短的命令下达语法(syntax)简介|
|DESCRIPTION|较为完整的说明，这部分最好仔细看看！|
|OPTIONS|针对 SYNOPSIS 部分中，有列举的所有可用的选项说明|
|COMMANDS|当这个程序(软件)在运行的时候，可以在此程序(软件)中下达的命令|
|FILES|这个程序或数据所使用或参考或连结到的某些文件|
|SEE ALSO|可以参考的，跟这个命令或数据有相关的其他说明！|
|EXAMPLE|一些可以参考的范例|
|BUGS|是否有相关的bug！|
