# 网盘链接检测工具 - 更新仓库

这是网盘链接检测工具的更新文件仓库。

## 文件结构

```
netdisk-checker-updates/
├── version.json          # 版本信息文件
├── updates/             # 更新文件目录
│   └── 网盘链接检测工具_v2.6.0_多源更新版.exe
└── README.md
```

## 更新说明

- 程序会自动从jsDelivr CDN检查更新
- 支持多源更新机制，确保更新成功率
- 强制更新确保用户使用最新版本

## 部署说明

1. 将新版本的exe文件上传到`updates/`目录
2. 更新`version.json`中的版本号和发布说明
3. 提交到GitHub仓库
4. jsDelivr CDN会自动同步更新 
