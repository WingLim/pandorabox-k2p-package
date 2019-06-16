# pandorabox-packages
因为我自己的K2P刷了官方的 PandoraBox，不想使用 Lean 大佬的，因为集成了太多东西，想要精简一点，然后再自己安装软件。

SDK 来自 PandoraBox 官方 ：[PandoraBox-SDK-ralink-mt7621_gcc-5.5.0_uClibc-1.0.x.Linux-x86_64.tar.xz](https://downloads.pangubox.com/sdk_for_pear/PandoraBox-SDK-ralink-mt7621_gcc-5.5.0_uClibc-1.0.x.Linux-x86_64.tar.xz)

## frpc & frps

Makefile 来自 [openwrt-frp](https://github.com/kuoruan/openwrt-frp)

建议使用 kuoruan 的 luci 界面 [luci-app-frpc](https://github.com/kuoruan/luci-app-frpc) 

当然官方的也可以。



## V2ray

Makefile 来自 [openwrt-v2ray](<https://github.com/kuoruan/openwrt-v2ray>)

PandoraBox 的官方源是有的，但是太大了，需要 9MB 的空间才能安装

需要注意的是，使用 v2ray 之前安装 luci-app-ssr-plus 来管理