MDK、keil for ARM，都是同一个东西。ARM公司现在统一使用MDK-ARM的称呼，MDK的设备数据库中有很多厂商的芯片，是专为微控制器开发的工具，为满足基于MCU进行嵌入式软件开发的工程师需求而设计，支持ARM7，ARM9，Cortex-M4/M3/M1，Cortex-R0/R3/R4等。

下载链接： https://blog.csdn.net/Simon223/article/details/105090189

在使用Keil 5(MDK 5)进行嵌入式开发时，Pack Installer是安装和管理软件包的重要工具。然而，许多用户在尝试通过Pack Installer下载软件包时，经常遇到各种问题，导致无法顺利安装所需的包。本文提供了一种替代方法，帮助用户解决Pack Installer下载不了包的问题。 解决方案

手动下载软件包
当Pack Installer无法正常下载软件包时，用户可以手动从Keil官网下载所需的软件包。以下是具体步骤：

访问Keil官网：前往Keil官网的MDK5 Software Packs页面。
查找所需软件包：在页面上找到并下载你需要的软件包，例如RT-Thread的包。
导入已下载的软件包
下载完成后，按照以下步骤将软件包导入到Keil 5中：

打开Keil 5：启动Keil 5开发环境。
导入软件包：
    在Keil 5中，点击菜单栏的Pack Installer选项。
    在弹出的窗口中，选择Import选项。
    浏览并选择你之前下载的软件包文件（通常是.pack格式）。
    点击Open按钮，开始导入过程。
