# 华硕RT-AC86U86U86U：刷官改/梅林改版系统和挂载虚拟内存教程

------

### 步骤一、固件下载

- 【梅林改版】：基于梅林固件修改，添加软件中心，有更多的功能和 bug 修复。
- 【官改】：基于官方固件修改，添加软件中心，ROG 红色界面，支持 AiMesh，更新较快。
 ```
 好用程度差别不大，稳定性也基本无差，选哪个固件基于个人喜好。固件作者：sadog
 ```
- 【梅林改版】[384.13_1 下载](https://github.com/masonvip/AC86U-meilin/blob/master/file/RT-AC86U_384.13_1_cferom_ubi-koolshare.w)
- 【官改】[384_45717 下载](https://github.com/masonvip/AC86U-meilin/blob/master/file/RT-AC86U_384_45717_koolshare_cferom_ubi-0627.w)



------

### 步骤二、升级固件

`注：以梅林改版为例，请使用 Chrome 浏览器进行操作。`

1. 路由器连接电脑，网页端进入路由器后台；
2. 选择【系统管理】-【固件升级】，选择 ```.w``` 后缀的官改固件，上传即可。

![](https://github.com/masonvip/AC86U-meilin/blob/master/picture/01.png?raw=true)
![耐心等待完成](https://upload-images.jianshu.io/upload_images/12894454-73f77017e12b08a5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 完成后请连上网络。

![ROG 信仰红色界面](https://upload-images.jianshu.io/upload_images/12894454-90b44ad75559b8db.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

------

### 步骤三、更新【软件中心】

进入【软件中心】，点击更新到最新。

![](https://upload-images.jianshu.io/upload_images/12894454-24bd93ac84e4da0f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

------

### 步骤四、安装插件

1. 插件：[点击下载](https://github.com/hq450/fancyss/blob/master/fancyss_hnd/shadowsocks.tar.gz)，进入网站点击```Download```进行下载。
2. 进入路由器【软件中心】-【离线安装】，选择下载好的文件后缀名为``` .gz```，上传并安装。

![](https://upload-images.jianshu.io/upload_images/12894454-59e7b8f4be19d7e8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

------

### 步骤五、安装虚拟内存

进入【软件中心】-【未安装】里找到【虚拟内存】并安装。
```注：如果你安装插件不多，无需挂载虚拟内存，此步骤可省略。86U 剩余内存不多，挂载虚拟内存系统的稳定性会增强。```

![](https://upload-images.jianshu.io/upload_images/12894454-1dd9de26907b5403.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 先将 U盘格式为 ext4 格式，方法：[U盘如何格式化为 ext3 ext4 格式](https://www.jianshu.com/p/85039ac096c3)；
2. 将 U盘插在路由器背面 USB（2.0 或 3.0 接口均可）上，打开【软件中心】-【虚拟内存】，会显示 U盘信息；```如不显示说明格式不对，请重新操作上面第 1 步```
3. 虚拟内存大小选择 512 MB 或 1G 均可，点击【创建虚拟内存】即可。

![](https://upload-images.jianshu.io/upload_images/12894454-f6e17f74963e72b1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 体验：

- 华硕路由器刷机非常简单，直接上传新固件即可完成。
- 现阶段千元内的路由器，不论颜值还是性能都非常优秀。

Q：家里宽带是 200M，为什么测速总是百兆？
A：请先检查```宽带猫```和```网线```是否都支持千兆，其次市面上很多价位在 100-300 元左右的路由器，宣传是千兆路由，但端口其实是百兆，不良商家虚假广告误导消费者，请大家购买时留意。

```声明：刷机的朋友认真请阅读本文，带来的风险请自行承担！```