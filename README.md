# 日常 Android 安装包

本仓库提供“日常”Android 安装包与 SHA-256 校验文件，源码保存在私有仓库。

## 下载与安装

1. 打开[最新版本](https://github.com/WZXsea/daily-android/releases/latest)，下载 `daily-0.1.4.apk`。同一签名支持覆盖安装 0.1.3。
2. 安装后输入服务器地址 `https://daily.wzx2002.icu`，以及从自己的网页版账号创建的个人访问令牌（PAT）。令牌由你在首次连接时输入，随后保存在手机受保护存储。
3. 下载同一版本的 `SHA256SUMS` 校验 APK。

0.1.4 改进 Markdown 加粗和公式渲染，对历史双重转义的独立公式段落提供阅读兼容；表格增加“复制 Markdown 表格”按钮，窄屏表格支持横向滚动。0.1.3 调整输入法布局并精简笔记本选单。0.1.2 增加桌面快捷记录小部件、在线状态和绿色“＋”入口。

包名：`icu.wzx2002.daily`。目标设备：K80 Pro / Android 14。APK 通过 Android 14 模拟器的启动、小部件和本地存储测试；输入法布局以 K80 Pro 安装后的检查为准。

本应用基于 [Memos](https://github.com/usememos/memos) 修改。原项目的 MIT 许可见 [LICENSE](LICENSE)。
