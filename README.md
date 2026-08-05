# 成耀音视图Tools · 官方更新仓库

本仓库用于发布 **成耀音视图Tools** 的官方 Windows 安装包和在线更新清单。

## 当前版本

- 版本：v1.0.3
- 更新清单：[latest.json](./latest.json)
- 国内镜像：[腾讯云 COS](https://chengyao-tools-updates-1257980096.cos.ap-guangzhou.myqcloud.com/ChengYaoTools_v1.0.3_Setup.exe)
- 备用下载：[GitHub Releases](https://github.com/easonl0528/ChengYaoTools-Updates/releases/latest)
- SHA-256：`0A86049324DDF6B44EF77ECBC8EDF1D9C8465EB9F552968AB8162419339F2F9E`

## 更新方式

软件会定期读取更新清单，发现新版本后显示更新说明。安装包优先从腾讯云 COS 国内镜像下载；国内镜像不可用时自动切换到 GitHub Releases。

下载完成后会核对文件大小和 SHA-256；校验不一致的安装包不会运行。

> 安全提示：本仓库不会使用来源不明的 GitHub 公共代理或第三方下载站作为官方更新源。
