# 使用已经编译好的ipk的请注意：可能需要执行chmod a+x /etc/init.d/synology 来给脚本执行权限
# luci-app-synology
openwrt上黑群晖的配置界面
依赖qemu和kvm.目前ipk仅支持intel-kvm可以根据自己情况修改依赖项。

# x86_64的安装代码:
```
wget https://github.com/ykxVK8yL5L/luci-app-synology/releases/download/v0.0.1/luci-app-synology_git-23.006.29676-959a219_all.ipk
opkg install luci-app-synology_git-22.100.34822-fdcc7df_all.ipk
```
## 黑群晖7.1视频演示:<https://youtu.be/Ueex9PRB3zg>   
5.71的数据盘最少40g吧，30g也许也可以。20G在安装后做存储池的时候会提示空间不足。raid会将数据盘容量打折。
## 黑群晖6.17视频演示:<https://youtu.be/qSxtZwxPGUc>
