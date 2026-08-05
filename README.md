# 成耀音视图Tools · 官方更新仓库

本仓库用于发布 **成耀音视图Tools** 的官方 Windows 安装包和在线更新清单。

## 当前版本

- 版本：v1.0.3
- 更新清单：[latest.json](./latest.json)
- 安装包：[GitHub Releases](https://github.com/easonl0528/ChengYaoTools-Updates/releases/latest)
- SHA-256：`0A86049324DDF6B44EF77ECBC8EDF1D9C8465EB9F552968AB8162419339F2F9E`

## 更新方式

软件会定期读取 `latest.json`，发现新版本后显示更新说明。下载完成后会核对文件大小和 SHA-256；校验不一致的安装包不会运行。

更新器支持多个下载地址：将来配置腾讯云 COS 等国内对象存储后，可优先走国内 HTTPS 地址；国内源不可用时自动切换到 GitHub Releases。

> 安全提示：本仓库不会使用来源不明的 GitHub 公共代理或第三方下载站作为官方更新源。
