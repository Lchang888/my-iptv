# 山西联通 IPTV 源

自动更新的山西联通 IPTV 直播源，基于组播源抓取。

## 📺 源地址

- **M3U文件**: `m3u/山西联通.m3u`
- **TXT文件**: `txt/山西联通.txt`

## 🔄 更新机制

- 使用 GitHub Actions 每天自动更新 2 次
- 从 [cqshushu](https://blog.cqshushu.com/multicast-iptv) 抓取最新组播源
- 只保留山西联通的源

## 🚀 使用方法

### 1. 直接使用 M3U 文件
```
https://raw.githubusercontent.com/sheriffcheng-gif/my-iptv/main/m3u/山西联通.m3u
```

### 2. 在播放器中导入
- **IPTV播放器**: 直接导入上面的 M3U 地址
- **Emby/Jellyfin**: 在 IPTV 插件中添加 M3U 地址
- **xTeVe**: 在 M3U 配置中填入地址

### 3. GitHub Proxy 加速（可选）
如果 GitHub 访问慢，可以使用加速代理：
```
https://gh-proxy.com/https://raw.githubusercontent.com/sheriffcheng-gif/my-iptv/main/m3u/山西联通.m3u
```

## 📋 更新日志

- 自动更新，无需手动维护
- 每天 UTC 00:00 和 12:00 各更新一次

## 🔧 手动触发更新

在 GitHub 仓库页面，点击 Actions -> Update IPTV Sources -> Run workflow

## 📝 说明

- 源来自运营商组播地址，需要在对应网络环境下使用
- 山西联通宽带用户可直接使用
- 其他运营商用户可能需要使用对应的源

## 🙏 致谢

原始抓取脚本来自 [jia070310/4K-IPTV-M3U](https://github.com/jia070310/4K-IPTV-M3U)
