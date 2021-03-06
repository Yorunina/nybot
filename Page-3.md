#基础补充插件配置

##基础补充插件是什么
>请注意，目前版本并不推荐使用该插件，该插件已在General规范推出之后（先驱1210版本之后），整合包默认删除此插件。

>是我自己用来练手，瞎写的一个烂插件  
其功能包括bot状态查询、自动同意好友、自动同意群邀请、加好友后自动发送消息等。

##如何配置基础补充插件  

如果开启了基础补充插件，那么他会生成一个“【运行目录】/Config/基础补充”文件夹  

在这个文件夹内，需要新建一个“配置.ini”以供其读取设置状态，否则只会采用默认配置。  
  
![Picture](/pic/12.png "配置文件位置示例")  

目前版本下，配置文件只有几项，分别是：

1. 主人
   - 用于设定该插件的主人权限，用于窗口播报
2. 自称
   - 用于规范某些关键词，如\*[自称]退群、\*[自称]状态
3. 自动同意好友申请
   - 在“真”的状态下，会自动同意好友申请
4. 自动同意群申请
   - 在“真”的状态下，会自动同意群申请
5. 自动缓存群成员列表
   - 在“真”的状态下，会在某些情况下将当前群的群成员json写出到某个文件中
6. 好友添加消息
   - 在被添加为好友(包括单向好友)时，会自动回复该配置项下的内容

一个设置好的配置文件形式如下图所示：

![Picture](/pic/13.png "配置文件示例") 

##基本补充插件提供了什么功能  

>下文中，所有的[自称]代表你在配置文件中填写的“自称”  

   1. 退群功能
      - 触发指令：*[自称]退群
   2. 查询状态
      - 触发指令：*[自称]状态
   3. 取图链功能
      - 触发指令：*图链[图片]
   4. 在添加好友后自动追加回复 
   5. 自动同意好友申请
   6. 自动同意加群邀请
   7. 自动缓存群成员文件

截止到目前，功能只有以上几种，整体功能会随着用户的要求而不断增加，但始终会保持一个“轻量级”的状态，不会开发出较大型的功能。