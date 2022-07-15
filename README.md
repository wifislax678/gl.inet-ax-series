## GL.iNet Slate-AXT1800/Flint-AX1800 Openwrt固件

固件经由Github Actions自动云编译，性能及稳定性请自行测试

***此固件无官方界面

## 固件相关

固件编译脚本fork自[Road-tech](https://github.com/Road-tech)的[Custom_firmware_for_gl-inet_AXT1800](https://github.com/Road-tech/Custom_firmware_for_gl-inet_AXT1800)并作出定制

编译配置文件参考了[JiaY-shi](https://github.com/JiaY-shi)的[build-gl.inet](https://github.com/JiaY-shi/build-gl.inet)，以及[monw](https://github.com/monw)的[gl-infra-builder](https://github.com/monw/gl-infra-builder)

此固件基于[gl-inet](https://github.com/gl-inet)的官方开源仓库[gl-infra-builder](https://github.com/gl-inet/gl-infra-builder)，属Openwrt 21.02，提供5.4及4.4内核两个版本

如需定制，请自行fork及修改

## Openwrt设定

- 预设IP: 192.168.1.20

- 预设密码: 无

- 预设WiFi SSID：GL.iNet-AX / GL.iNet-AX-5G

- LTE/4G 接口自动设置

- 预设使用Argon主题

- 集成插件：
  - luci-app-accesscontrol	上网时间控制
  - luci-app-openclash	    Clash代理客户端
  - luci-app-ddns	          动态域名DNS
  - luci-app-passwall2	    科学上网
  - luci-app-autoreboot	    定时自动重启
  - luci-app-ttyd	          网页终端命令行
  - luci-app-wol	          网络唤醒
  - luci-app-argon-config	  Argon主题设置
  - luci-app-cpufreq	      CPU频率调制
  - luci-app-ramfree	      内存释放
  - luci-app-qos	          网络流量服务质量(QoS)流控
  - luci-app-usb-printer	  USB网络打印
  - luci-app-vlmcsd	        KMS激活服务器
  - luci-app-wrtbwmon	      实时流量监控
  - luci-app-upnp	          通用即插即用UPnP（端口自动转发）
  - luci-app-wifischedule	  WiFi计划
  - luci-app-qbittorrent	  BT下载工具
  - luci-app-vsftp	        FTP服务器
  - luci-app-diskman	      磁盘管理
  - luci-app-hd-idle	      硬盘休眠

## 关于自动编译脚本

自动编译脚本源自[P3TERX](https://github.com/P3TERX)/[Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

脚本使用说明：[English](https://github.com/P3TERX/Actions-OpenWrt) | [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)
