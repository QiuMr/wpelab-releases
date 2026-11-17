# WPELab 发布库

这里只放 **安装包与更新清单**，不放源码（源码在私有仓库）。

每次发版由 `.github/workflows/release.yml` 自动写入：

- `WPELab-<版本>-Setup.exe` —— 安装包
- `WPELab-<版本>-win64.exe` —— 便携版
- `latest.json` —— 自动更新读取的清单（包含版本号、下载地址、sha256、体积）

**请不要手动修改 Release 内容**，否则客户端的自动更新校验（sha256）会失败。
