# pandorabox-packages
因为我自己的K2P刷了官方的 PandoraBox，不想使用 Lean 大佬的，因为集成了太多东西，想要精简一点，然后再自己安装软件。

但是因为 PandoraBox 使用的是 mipsel_1004kc_dsp 的架构，而常见的是 mipsel_24kc ，加上 PandoraBox 最新版是 2019-02-01 编译的，有的软件已经更新了，在 PandoraBox 上却无法使用。

所以从 PandoraBox 上下载了 SDK 来自己编译，同时使用 UPX 来压缩二进制文件再打包成 ipk ，节省空间。

SDK 地址 ：[PandoraBox-SDK-ralink-mt7621_gcc-5.5.0_uClibc-1.0.x.Linux-x86_64.tar.xz](https://downloads.pangubox.com/sdk_for_pear/PandoraBox-SDK-ralink-mt7621_gcc-5.5.0_uClibc-1.0.x.Linux-x86_64.tar.xz)

## frpc

Makefile 来自 [openwrt-frp](https://github.com/kuoruan/openwrt-frp)

建议使用 kuoruan 的 luci 界面 [luci-app-frpc](https://github.com/kuoruan/luci-app-frpc) 




## V2ray

Makefile 来自 [openwrt-v2ray](<https://github.com/kuoruan/openwrt-v2ray>)

PandoraBox 的官方源是有的，但是太大了，需要 9MB 的空间才能安装

这个是内置 jsonem ，而不是使用 v2ctl 来读取 json 
