---
icon: editor
# 设置写作时间
date: 2023-09-07
# 一个页面可以有多个分类
category:
  - Win
# 一个页面可以有多个标签
tag:
  - 教程
  - 代理
  - Clash
  - Windows
# 此页面会在文章列表置顶
sticky: true
# 禁止编辑此页链接
editLink: false
---

# Clash for Windows使用教程



## 安装软件

::: tip

软件下载：https://github.com/Fndroid/clash_for_windows_pkg/releases

根据电脑CPU和操作系统下载对应的版本即可。

如果找不到对应的版本，点击 `Show all 15 assets`显示全部版本。

以下操作以`CPU：x86_64，系统：Windows`为例

:::

![image-20230907152627037](assets/images/image-20230907152627037.png)

点击之后，如下图所示。显示全部版本。

![image-20230907152028864](assets/images/image-20230907152028864.png)



双击安装包开始安装，默认安装即可。

![image-20230907140848936](assets/images/image-20230907140848936.png)



安装完成之后，如下图所示，默认是英文。

![image-20230907140926933](assets/images/image-20230907140926933.png)



右击图标，退出软件。如下图所示。

![image-20230907141449566](assets/images/image-20230907141449566.png)





## 汉化软件
::: tip
汉化补丁下载：https://github.com/BoyceLig/Clash_Chinese_Patch/releases

:::

![image-20230907151209162](assets/images/image-20230907151209162.png)

解压app.7z压缩包，得到app.asar文件。

![image-20230907141305479](assets/images/image-20230907141305479.png)



在桌面找到`Clash for Windows`软件图标，右击图标，点击`打开文件所在的位置`，再进入`resources`文件夹。

把刚刚解压的`app.asar`文件替换掉当前目录下`app.asar`文件。

![image-20230907141638254](assets/images/image-20230907141638254.png)

![image-20230907135532150](assets/images/image-20230907135532150.png)



替换完成后，回到桌面双击打开`Clash for Windows`软件图标。如下图所示，软件已经完成汉化。

![image-20230907142040176](assets/images/image-20230907142040176.png)



## 配置文件（订阅）

点击配置，输入订阅URL，然后点击下载。

::: tip
免费URL推荐：https://github.com/WilliamStar007/ClashX-V2Ray-TopFreeProxy

:::


![image-20230907142220628](assets/images/image-20230907142220628.png)



配置文件下载成功后，如下图所示。

![image-20230907142409076](assets/images/image-20230907142409076.png)



## 配置代理

::: tip
配置文件（订阅URL）不同，在该界面展示的代理方式也不相同，根据情况选择使用即可。

:::
点击代理，在代理界面可以看到，刚刚下载的配置文件节点内容，该配置文件是通过规则进行代理。

1、点击`规则`，再次点击`节点选择`后展开节点列表，再点击延迟检测，查看各节点的延迟时间。

2、选择延迟时间短的节点即可，这里选择`_US_美国`节点。

![image-20230907145758809](assets/images/image-20230907145758809.png)



## 启动代理

点击常规，在常规界面，开启`系统代理`。如下图所示

![image-20230907143509821](assets/images/image-20230907143509821.png)



## 验证代理

进入到浏览器，输入`google.com`，出现下图所示，代表成功。

![image-20230907143541592](assets/images/image-20230907143541592.png)

## ADC 资源群

::: tip
扫码添加微信，备注 `ADC` 即可。

:::

![ADC 资源群](/assets/images/ADC-QrCode.jpg)