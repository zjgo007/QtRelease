# QtRelease
使用Qt制作的一些打包发布的程序，可直接运行，博客地址https://blog.csdn.net/zjgo007

# 离线地图下载工具（瓦片地图）
QML中加载离线瓦片地图时，就需要将瓦片地图下载到本地，并按照规定的瓦片命名方式进行命名。因此我制作了该瓦片地图下载工具，该工具可选择不同地图类型进行下载。

> 功能：
> 
> 自定义地图源编号方式
> 
> 自定义地图瓦片的命名规则
> 
> 自定义下载地图的层级范围
> 
> 自定义下载地图经纬度区间，不勾选表示全部经/纬度
> 
> 自定义下载地图保存位置（必填）
说明：
Z：瓦片地图的层级，从0开始

X：瓦片地图X编码

Y：瓦片地图Y编码

该工具默认已设置好内置下载地图的编码及命名规则

![tools](https://img-blog.csdnimg.cn/20210613185608175.PNG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pqZ28wMDc=,size_16,color_FFFFFF,t_70)
