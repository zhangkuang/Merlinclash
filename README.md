# koolshare 官改固件刷 Merlinclash 教程

# <font color=red>如果安装了科学上网，先关闭或者卸载</font>

## TG群组
- [clash详细说明](https://t.me/merlinclashcat)
- [讨论组](https://t.me/meilinchajian)
- [clash文件下载](https://t.me/merlinclashfile)

## 1、 先确认自己的机器型号

> 下面的表格列出了各个不同版本fancyss对固件/平台/架构等的支持情况，以及不同fancyss对一些功能/特性的支持情况，对应的文字说明请见下文。

- [机型/固件支持（表格版）](https://github.com/hq450/fancyss#%E6%9C%BA%E5%9E%8B%E5%9B%BA%E4%BB%B6%E6%94%AF%E6%8C%81%E8%A1%A8%E6%A0%BC%E7%89%88)

### ctrl + F 搜索路由器型号 确定路由器 <font color="red">架构</font>

## 2、 [下载linux版clash](https://github.com/Dreamacro/clash/releases)

## 3、 打开路由器管理后台，选择左侧软件中心，然后选择离线安装

**提示1：** 如果提示检测到离线安装包名有非法关键词。开启路由器的SSH功能，登录并输入以下命令后，再进行离线安装。(arm380/X7.x版本固件需要请将软件中心更新到1.4.8及以上)

[参考教程视频](https://www.youtube.com/watch?v=Pigjr1kRj2A)

```bash
sed -i 's/\tdetect_package/\t# detect_package/g' /koolshare/scripts/ks_tar_install.sh
```

## 4、参考教程 
- [TG](https://t.me/merlinclashcat)
- [教程1](https://zxfccmm.cn/hua-shuo-rt-ac86u-an-zhuang-merlin-clash/)
- [教程2](https://github.com/KOP-XIAO/Clash-Merlin/wiki)
