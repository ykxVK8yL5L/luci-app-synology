# 使用已经编译好的ipk的请注意：可能需要执行chmod a+x /etc/init.d/synology 来给脚本执行权限
# luci-app-synology
openwrt上黑群晖的配置界面
依赖qemu和kvm.目前ipk仅支持intel-kvm可以根据自己情况修改依赖项。

# x86_64的安装代码:
```
wget https://github.com/ykxVK8yL5L/luci-app-synology/releases/download/v0.0.1/luci-app-synology_git-22.100.18696-116e6fb_all.ipk
opkg install luci-app-synology_git-22.100.18696-116e6fb_all.ipk
```

## 黑群晖6.17视频演示:<https://youtu.be/qSxtZwxPGUc>
