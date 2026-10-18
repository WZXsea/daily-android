# 日常 Android 安装包

本仓库提供“日常”Android 安装包与 SHA-256 校验文件，源码保存在私有仓库。

## 下载与安装

1. 打开[最新版本](https://github.com/WZXsea/daily-android/releases/latest)，下载 `daily-0.1.2.apk`。同一签名支持覆盖安装 0.1.1。
2. 安装后输入服务器地址 `https://daily.wzx2002.icu`，以及从自己的网页版账号创建的个人访问令牌（PAT）。令牌由你在首次连接时输入，随后保存在手机受保护存储。
3. 可下载同一版本的 `SHA256SUMS` 校验 APK。0.1.2 的 SHA-256 为 `6514e369ec0d72e46c52496b16d1d05a5ea36c28f6c3a50ebedbc316d01c5fd7`。

0.1.2 增加“日常 · 快捷记录”桌面小部件，点击即可打开个人笔记本的新建弹窗。手机顶部显示在线状态并可切换个人笔记本，笔记列表底部提供快捷“＋”入口。

包名：`icu.wzx2002.daily`。目标设备：K80 Pro / Android 14。0.1.2 已通过 Android 14 模拟器的启动、小部件和本地存储测试；K80 Pro 真机体验以安装后的检查为准。

本应用基于 [Memos](https://github.com/usememos/memos) 修改。原项目的 MIT 许可见 [LICENSE](LICENSE)。
