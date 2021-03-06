---
name: 二进制安装
---

# 二进制安装

**目前只提供最近 5 次版本发布的二进制下载，更多版本下载请前往 [GitHub](https://github.com/gogits/gogs/releases?after=v0.6.15) 查看。**

所有的版本都支持 **MySQL** 和 **PostgreSQL** 作为数据库，并且均使用构建标签（build tags）**`redis memcache cert`** 进行构建（`v0.7.19` 之后不再使用 `redis memcache` 构建标签）。需要注意的是，不同的版本的支持状态有所不同，请根据实际的 Gogs 提示进行操作。

### v0.7.22 @ 2015-11-25

|系统名称|系统类型|SQLite|TiDB|PAM|下载|
|------|----|------|----|---|--------|
|Linux|386|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.22_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.22_linux_386.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_linux_386.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_linux_386.tar.gz)|
|Linux|amd64|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.22_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.22_linux_amd64.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_linux_amd64.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_linux_amd64.tar.gz)|
|Linux|arm|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.22_linux_arm.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_linux_arm.zip)|
|Raspberry Pi|v2|✅|❌|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.22_raspi2.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_raspi2.zip)|
|Windows|386|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.22_windows_386.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_windows_386.zip)|
|Windows|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.22_windows_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_windows_amd64.zip)|
|Mac OS|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.22_darwin_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.22_darwin_amd64.zip)|

### v0.7.19 @ 2015-11-21

|系统名称|系统类型|SQLite|TiDB|PAM|下载|
|------|----|------|----|---|--------|
|Linux|386|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.19_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.19_linux_386.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_linux_386.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_linux_386.tar.gz)|
|Linux|amd64|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.19_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.19_linux_amd64.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_linux_amd64.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_linux_amd64.tar.gz)|
|Linux|arm|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.19_linux_arm.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_linux_arm.zip)|
|Raspberry Pi|v2|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.19_raspi2.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_raspi2.zip)|
|Windows|386|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.19_windows_386.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_windows_386.zip)|
|Windows|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.19_windows_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_windows_amd64.zip)|
|Mac OS|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.19_darwin_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.19_darwin_amd64.zip)|

### v0.7.6 @ 2015-11-12

|系统名称|系统类型|SQLite|TiDB|PAM|下载|
|------|----|------|----|---|--------|
|Linux|386|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.6_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.6_linux_386.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_linux_386.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_linux_386.tar.gz)|
|Linux|amd64|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.6_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.6_linux_amd64.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_linux_amd64.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_linux_amd64.tar.gz)|
|Linux|arm|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.6_linux_arm.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_linux_arm.zip)|
|Raspberry Pi|v2|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.6_raspi2.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_raspi2.zip)|
|Windows|386|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.6_windows_386.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_windows_386.zip)|
|Windows|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.6_windows_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_windows_amd64.zip)|
|Mac OS|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.6_darwin_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.6_darwin_amd64.zip)|

### v0.7.0 @ 2015-11-08

|系统名称|系统类型|SQLite|TiDB|PAM|下载|
|------|----|------|----|---|--------|
|Linux|386|✅|❌|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.0_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.0_linux_386.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_linux_386.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_linux_386.tar.gz)|
|Linux|amd64|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.0_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/gogs_v0.7.0_linux_amd64.tar.gz) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_linux_amd64.zip) \| [TAR.GZ](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_linux_amd64.tar.gz)|
|Linux|arm|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.0_linux_arm.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_linux_arm.zip)|
|Raspberry Pi|v2|✅|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.0_raspi2.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_raspi2.zip)|
|Windows|386|❌|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.0_windows_386.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_windows_386.zip)|
|Windows|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.0_windows_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_windows_amd64.zip)|
|Mac OS|amd64|✅|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/gogs_v0.7.0_darwin_amd64.zip) - CDN: [ZIP](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.7.0_darwin_amd64.zip)|

### v0.6.15 @ 2015-09-26

|系统名称|系统类型|SQLite|TiDB|PAM|下载|
|------|----|------|----|---|--------|
|Linux|386|✅|❌|✅|[CDN](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.6.15_linux_386.zip) - [GitHub](https://github.com/gogits/gogs/releases/tag/v0.6.15)|
|Linux|amd64|✅|✅|✅|[CDN](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.6.15_linux_amd64.zip) - [GitHub](https://github.com/gogits/gogs/releases/tag/v0.6.15)|
|Windows|386|❌|✅|❌|[CDN](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.6.15_windows_386.zip) - [GitHub](https://github.com/gogits/gogs/releases/tag/v0.6.15)|
|Windows|amd64|✅|✅|❌|[CDN](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.6.15_windows_amd64.zip) - [GitHub](https://github.com/gogits/gogs/releases/tag/v0.6.15)|
|Mac OS|amd64|✅|✅|❌|[CDN](http://7d9nal.com2.z0.glb.qiniucdn.com/gogs_v0.6.15_darwin_amd64.zip) - [GitHub](https://github.com/gogits/gogs/releases/tag/v0.6.15)|

## 如何使用下载好的压缩包？

1. 解压压缩包。
2. 使用命令 `cd` 进入到刚刚创建的目录。
3. 执行命令 `./gogs web`，然后，就没有然后了。

## 如何通过二进制升级？

1. 下载最新版的压缩包。
2. 删除当前的 `templates` 目录。
3. 解压压缩包并将所有内容复制粘贴到相应（当前）的位置。

安装完成后可继续参照 [配置与运行](configuration_and_run.html)。
