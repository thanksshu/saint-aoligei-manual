# 加入游戏

## 前言

我们使用了第三方登录服务实现验证，即**不要求正版登录**就可以游玩，但是：

!> 请确保你拥有**正版**的 Minecraft Java Edition
!> 不要求正版登录仅仅是为了给玩家提供方便，并不代表我们认可盗版游戏

关于于这篇教程的时效性：

!> 如果日后有认证服务、游戏版本、启动器版本、JAVA 版本方面的变动，不保证能随时更新此段教程（尤其是图片），请**自行努力**，如果有较为严重的问题再请[联系我们](contact)

## 先从 JAVA 开始

众所周知，Minecraft 的运行需要 JAVA ——如果你确保拥有合适可用的 Java 版本，直接跳过这一节便是

可以使用 [Oracle Java](https://www.java.com)

也可以使用 [BellSoft](https://bell-sw.com/pages/downloads/)

## 准备第三方帐号

请前往 [Little Skin](https://littlesk.in/) 注册帐号

## 配置启动器

请在注册后请于 [Little Skin 用户主页](https://littlesk.in/user) 按照「快速配置启动器」内指示配置

或者

参考 [Little Skin 相关文档](https://manual.littlesk.in/advanced/yggdrasil.html#在客户端使用)，请注意替换相应 API 网址

!> 2020.11.29 HMCL 网站出现问题，下载转至(https://ci.huangyuhui.net/job/HMCL/)，选择`175`或者更高以下载

<!-- 注意：正如前面所说，由于我们使用第三方登录服务，就需要启动器支持自定义 [Yggdrasil API](https://github.com/yushijinhun/authlib-injector/wiki/Yggdrasil-服务端技术规范) 服务器：


以下以

- HMCL 3.3.170 做启动器
- Minecraft 1.15.2 选为游戏版本
- [Little Skin](https://littlesk.in/) 为认证服务器

进行配置：

1. 打开 HMCL 的「新建账户」界面；如果这是首次打开 HMCL，这个界面将会在启动时弹出
   ![](_media/launcher-conf/2.png)
   ![](_media/launcher-conf/3.png)
   ![](_media/launcher-conf/4.png)
   这是首次打开 HMCL 的样子：
   ![](_media/launcher-conf/1.png)

2. 选择登录方式为「外置登录（authlib-injector）」：
   ![](_media/launcher-conf/5.png)

3. 点击「+」，在接下来的窗口中填入*认证服务器地址*
   ![](_media/launcher-conf/6.png)
   ![](_media/launcher-conf/7.png)
   ![](_media/launcher-conf/8.png)

4. 填入在 [Blessing Skin Demo](https://skin.prinzeugen.net/) 注册的用户名密码并确定
   ![](_media/launcher-conf/9.png)
-->

5. 安装 1.16.4 版本
   ![](_media/launcher-conf/10.png)
   ![](_media/launcher-conf/11.png)

   如果下载遇到问题，可尝试更换源，这里便使用了官方源：

   ![](_media/launcher-conf/12.png)
   ![](_media/launcher-conf/13.png)
   ![](_media/launcher-conf/14.png)
   ![](_media/launcher-conf/15.png)

6. 点击启动游戏
   ![](_media/launcher-conf/16.png) -->

## 加入游戏 :id=join-game

上一节最后会将游戏启动（如果一切配置无恙），

这里将讲述如何加入我们的服务器

1. 启动游戏后在主界面选择「多人游戏」（示例中已经进行了[语言调整](faq?id=调整游戏语言)）
   ![](_media/game-server-conf/1.png)
   ![](_media/game-server-conf/2.png)
2. 填入*服务器地址*，服务器名称不要求一致，可自定义
   ![](_media/game-server-conf/3.png)
3. 双击服务器以加入游戏
   ![](_media/game-server-conf/4.png)
