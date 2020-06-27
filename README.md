# 华硕RT-AC86U：刷官改/梅林改版系统和挂载虚拟内存教程

## 固件区别

>- **梅林改版固件**：基于梅林固件修改，添加软件中心，有更多的功能和 bug 修复，新版本支持 AiMesh。
>- **官改固件**：基于官方固件修改，添加软件中心，ROG 红色信仰界面，支持 AiMesh，更新较快。

好用程度，稳定性差别不大，选哪个固件基于个人喜好。

## 步骤1 刷机（以梅林改版为例）

* 路由器连接电脑，网页端进入路由器后台；
* 点选【系统管理】-【固件升级】，选择下载好后缀为 `.w` 的固件上传。

![](pic/00.png)

* 固件升级约 3 分钟。

![](pic/01.png)

- 会自动重启，此时刷机完成。刷完建议恢复下出厂设置。
- 进入路由器后台，在【系统管理 】–【 系统设置】内将：`Format JFFS partition at next boot` 和 `Enable JFFS custom scripts and configs` 勾选，然后点击应用本页面，成功后重启路由器。
- 重启后先将路由器连上网络，进入软件中心更新到最新版本（如果有）。

![](pic/02.png)

---

## 步骤2 安装插件

* 进入「软件中心」-「离线安装」，选择下载好的文件（后缀名为 `.gz`）上传安装。

![](pic/03.png)

* 安装成功后回到【软件中心】，即可看到「科学上网」。

![](pic/04.png)

---
## 步骤3 订阅路线
* 打开路由器后台，点击「软件中心」-「科学上网」。

![05](pic/05.png)

* 点击「更新管理」。
* 把链接地址粘贴到「订阅地址管理」`🟡下图②处`。
* 然后点击「保存并订阅」。

![06](pic/06.png)

* 点击「账号设置」，「节点选择」里挑选一个路线。
* 打开科学上网开关。
* 点击「保存&应用」。此时连接路由器的所有设备均可科学上网了。

![07](pic/07.png)

## 固件和插件下载

![](pic/Q群.jpg)

