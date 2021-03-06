#如何使用整合包

##使用XQ整合包搭建Bot
>XQ是目前阶段我个人认为前景最好，当前功能最强大的一款QQ机器人框架——因此该整合选用的即是XQ框架

>本文中提到的整合包为下文链接中的General分支整合包！旧版整合包可能会出现各种各样奇怪的问题！请一定要注意这点！

>XQ主页：https://www.xianqubot.com/  
XQ社区：https://discourse.xianqubot.com/  
文中整合包地址：https://pan.baidu.com/s/16fFXhwm66PGJ7m81h4CpiA  
提取码：n00c

***
###下载先驱后


首先**下载整合包(Gnereal分支整合包)**，然后**解压**，整合包内应至少包括如下文件（如果此步出现报毒，是因为易语言被误杀，请将文件加入白名单）

![Picture](/pic/1.png "实际上会比这多一些")

当然，如果你下载的是[我所提供的整合包](https://pan.baidu.com/s/16fFXhwm66PGJ7m81h4CpiA)，那么文件应包括：

```
|app   ——CQ时代继承而来，存储数据用
|bin   ——内含核心.dll，请勿随意删除！
|data  ——铃心创建的资源保存位置，内含图片缓存等
|log   ——XQ自行创建的日志文件，可随意删除
|plugin ——CQ插件文件夹，内部应有.dll文件以及.ini配置信息 
|先驱.exe  ——应用程序，双击启动
╰————
```

>如果出现.exe丢失的情况，很有可能是杀毒软件误删，请自行去隔离区将其添加信任

双击打开**先驱.exe**，即可打开机器人。
***

###启动先驱后

![Picture](/pic/2.png "先驱当前版本的窗口")

>先驱的边栏分为日志(框架日志)、账号(账号管理)、插件(插件扩展)、设置(框架设置)这四个主要部分，下文均以二字简称来表述，不再重复全名。

```
日志：用于查看bot接受的消息和插件输出的log
账号：用于登录离线你的账号
插件：用于启用停用卸载重载你所安装的插件
设置：一些基础设置
```

在此处，我们只需<kbd>鼠标左键</kbd>一下账号管理就可以打开账号界面

![Picture](/pic/3.png "右击后")

然后通过<kbd>鼠标右键</kbd>一下空白面板，就可以添加QQ进行登录。

>值得注意的是，默认情况下XQ Bot使用的协议是PC协议，这意味着你无法再在PC端（电脑端）直接通过QQ登录Bot账号窥屏。但是用手机和平板是完全可以的。

<kbd>鼠标左键</kbd>添加QQ，然后按照提示进行登录即可

![Picture](/pic/4.png "登录界面，推荐扫码")

>用作Bot的QQ请务必保证是小号，最好不要将大号用作bot！之后章节可能会专门叙述为什么不要用大号/用大号做bot有哪些忧患。

![Picture](/pic/5.png "登录成功")

登录成功后，就可以看到类似于下文的效果——如果出现**无法找到可用的服务器**类似的情况，可能是因为XQ登录服务器出现问题导致的，一般几个小时后就可以得到解决。

***

###登录完成后

点击打开**插件扩展**界面，在我的整合包内，提供了两个插件分别是**铃心自定义**（作者：EPK）和**基础扩展**（作者：Yorunina）

![Picture](/pic/6.png "启用插件")

右键点击插件，然后单击启用即可。

>插件可以在[XQ社区](https://discuss.xianqubot.com/)获取，或者在某些地方（咳咳）
  
对于铃心自定义来说，你可以在右键插件打开的界面中选择设置插件，打开铃心自定义的GUI界面(用户交互界面)来进行关键词的设定。  

![Picture](/pic/8.png "设置插件")  

点击之后就可以看到铃心自定义的窗口了！恭喜！距离自己设定第一个关键词已经不远了！ 

![Picture](/pic/9.png "打开的窗口")  

关于这里的参数，大家可以自行设置，这里我只演示如何添加一个简单的自定义回复。  
首先，我们点击“基本设置”，右键空白位置，然后点击“添加”  

![Picture](/pic/10.png "添加回复")   

在唤出的界面中，我们尝试填入以下内容  

![Picture](/pic/11.png "打开的窗口")  

之后我们关闭窗口，点击保存，在群聊发送“早安”就可以看到回复了！
***
##完成搭建

至此，你已经通过[整合包](https://pan.baidu.com/s/16fFXhwm66PGJ7m81h4CpiA)搭建了一个基于XQ的Bot，恭喜！虽然目前该bot仅仅能运行在本地，但是你已经了解了基本的操作。挪到云端对你来说也几乎没有任何问题！

关于更多的插件以及插件的使用方法，会在本网页的其余界面介绍，如有疑问，可加本文群：1081033631 了解情况