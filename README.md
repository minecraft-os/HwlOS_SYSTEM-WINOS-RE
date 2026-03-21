# HwlOS_SYSTEM-WINOS-RE修改
<img width="48" height="48" alt="hwl" src="https://image2url.com/r2/default/files/1774086963353-cd309279-7a74-41bc-8d16-f1643dd49638.png" />
没错，HWLOS的真面目被我揭穿了。


感谢作者提供的精神支持：
@HardwareLab

本来我打算再搞多一点功能的，但是虚拟机崩了...导致更新只能停止到这了......


以下是系统截图：

<img width="1152" height="864" alt="HwlOS-2026-03-21-18-01-14" src="https://image2url.com/r2/default/files/1774087371675-e0825188-4c20-47c9-84a9-7e1ffa66e564.png" />

系统版本为23H2，按现在HotPE更新的进度来讲还不算老。


接下来来重点介绍一下这个版本的功能吧！


1.删除了HWLOS主桌面能打开的所有应用，只保留配置文件以及壁纸还有主文件

2.系统自带的Chrome++129版本更新为原版Chrome146版本（Tips:可以在chrome://flag中启用垂直标签页）

3.修复CMD，winver，taskmgr，Explorer这些PE都会用到的文件

4.使用FirPE同款WinXShell设置界面

5.添加了HarmonyDock

6.新增Cortana(作者：@柏雪闻采edge_A)

7.恢复mmc

8.给部分软件设置了Windows环境下内置的系统快捷键：

Win+Shift+S=打开QQ截图

Win+S=打开WinXShell设置界面

Win+L=打开WinXShell锁屏界面

Win+S=打开Everything

9.将系统自带的OpenWith替换为Figer的增强版OpenWith

虽然这个系统已经越来越像HotPE了，但是还是有很多的功能我是已经燃尽了...例如：

1.无法打开控制面板

2.系统托盘音量调整图标是残废的

3.CMD是半残废，因为只要存在的命令他都可以运行（不存在的就报错）

4.CTFMON输入法管理器能启动，但是点击切换输入法后会强制重启Explorer（意思就是切换不了输入法）

5.高级系统设置打不开（我明明已经补了它对应的MUI文件）

6.右键菜单个性化中的“随机背景”按钮没用

7.Winver只能显示版本号，其他都不显示。

目前我知道缺点也只有这些...能恢复这些功能已经是我的极限了... 
所以后续我将提供对应的工具，你们可以自行在我的Github仓库上下载并按照流程操作。

原HwlOS系统官网：<a href="https://hwlos.mysxl.cn">hwlos.mysxl.cn</a>

原版HotPE官网：<a href="https://www.hotpe.top">hotpe.top</a>

如果可以的话，你可以到我的个人空间来个一键三连码？
<a href="https://space.bilibili.com/3546636693277438">j进入个人空间</a>
