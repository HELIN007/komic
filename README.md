# Komic - 多源漫画阅读器

<p align="center">
  <img src="assets/logo.png" alt="Komic Logo" width="120"/>
</p>

<p align="center">
  <b>在线 + 本地 | AI 画质增强</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/版本-1.1.2-blue" alt="Version"/>
  <img src="https://img.shields.io/badge/平台-Android-green" alt="Platform"/>
  <img src="https://img.shields.io/badge/Flutter-Dart-02569B?logo=flutter" alt="Flutter"/>
</p>

---

## ✨ 功能亮点

### 📚 多源阅读，一站管理
- **Komga 服务器** — 连接你的 Komga 实例，浏览系列、书籍、阅读进度全自动同步
- **WebDAV 网盘** — 支持 WebDAV，远程流式阅读 ZIP/CBZ/EPUB
- **本地文件** — 支持 ZIP、CBZ、CBR、EPUB、PDF 及图片文件夹

### 🎯 专业阅读体验
- **多种阅读模式** — 单页 / 双页 / 条漫模式，左→右 / 右→左 / 上→下方向自由切换
- **双页拆分** — 横向跨页智能识别并拆分为两个独立页面 (Beta)
- **裁白边** — 自动检测并裁剪页面白边，最大化有效阅读区域 (Beta)
- **纸张纹理** — 自定义背景色与纸张纹理，打造沉浸式阅读氛围
- **点击区域自定义** — 根据习惯调整翻页触控区域大小
- **智能预加载** — 提前加载后续页面，翻页无等待

### 🤖 AI 画质增强
- 集成 **waifu2x-anime**、**RealESRGAN** 等多个 AI 模型
- 本地推理，无需联网，隐私安全
- 智能抢占：优先处理当前阅读页，体验流畅
- 增强结果自动缓存，避免重复处理

### 📥 离线下载
- 后台下载队列管理
- 支持散页下载 / 整包下载两种模式
- 断点续传、并发控制
- 按系列/来源分组管理

### 🔍 全局搜索
- 跨 Komga / WebDAV / 本地的统一搜索
- 搜索历史记录、按数据源分组显示

### 📊 阅读统计 (Beta)
- 记录每本书的阅读时长
- 可视化阅读数据

### 🎨 个性化定制
- 动态主题色 / 深色模式
- 触感反馈强度调节
- 通知提醒配置

---

## 📱 安装指南

### 系统要求
- **Android 5.0+**（API 21+）
- 建议 Android 8.0 及以上以获得最佳体验

### 安装步骤

1. 从 [Releases](../../releases) 页面下载最新版 APK 文件
2. 在手机上打开下载的 APK 文件
3. 如果提示「不允许安装未知来源应用」，请前往 **设置 → 安全 → 未知来源** 允许安装
4. 安装完成后打开应用即可使用

> ⚠️ 首次安装后需要输入**激活码**才能使用。请联系开发者获取激活码。

---

## 🚀 快速上手

### 1. 激活应用
打开应用后，输入激活码完成设备激活。

### 2. 添加数据源

#### Komga 服务器
设置 → 添加服务器 → 输入服务器地址、用户名和密码 → 连接 → 保存

#### WebDAV 网盘
设置 → 添加 WebDAV 服务器 → 输入地址和认证信息 → 可添加常用路径为书签

#### 本地文件
设置 → 权限管理 → 添加本地漫画路径 → 应用会自动扫描该目录下的漫画文件

### 3. 开始阅读
在首页「继续阅读」或对应书库中选择漫画，点击即可进入阅读器。

---

## 📋 支持格式

| 格式 | 扩展名 | 数据源 |
|------|--------|--------|
| ZIP 漫画包 | `.zip`, `.cbz` | 全部 |
| RAR 漫画包 | `.cbr`, `.rar` | 全部 |
| EPUB 电子书 | `.epub` | 全部 |
| PDF 文档 | `.pdf` | 全部 |
| 图片文件夹 | 文件夹内含图片 | 本地 |

---

## ❓ 常见问题

<details>
<summary><b>Q: 安装提示「包解析错误」怎么办？</b></summary>

请确认你的 Android 版本 ≥ 5.0。如果仍然无法安装，尝试下载完整版 APK（而非增量更新包）。
</details>

<details>
<summary><b>Q: AI 画质增强支持哪些设备？</b></summary>

AI 画质增强使用 NCNN 本地推理，需要一定的设备性能。建议使用 3GB 以上 RAM 的设备以获得流畅体验。
</details>

<details>
<summary><b>Q: 如何找回激活码？</b></summary>

请联系开发者，提供设备信息以重新获取或迁移激活码。
</details>

---

## 📬 反馈与交流

如有问题、建议或 Bug 反馈，欢迎通过以下方式联系：

- 📧 提交 [Issue](../../issues)
- 💬 加入交流群（TG群：@komic007，或者详见应用内「反馈交流」页面）

---

## ⚖️ 版权声明

**© 2026 Komic. All Rights Reserved.**

本软件为个人开发作品，仅供免费下载和个人使用。未经作者书面许可：

- ❌ **禁止** 反编译、反汇编或以其他方式逆向工程本软件
- ❌ **禁止** 修改、改编或创建本软件的衍生作品
- ❌ **禁止** 将本软件用于任何商业目的或进行二次分发
- ❌ **禁止** 移除或篡改软件中的版权标识与激活机制

违反上述条款的行为将被追究相应法律责任。

---

## ☕ 请作者喝杯咖啡

如果 Komic 对你有帮助，欢迎请作者喝杯咖啡 ☕ 你的支持是持续更新的最大动力！

<p align="center">
  <img src="assets/ali_pay_qr.jpg" alt="支付宝" width="200"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/wechat_pay_qr.JPG" alt="微信支付" width="200"/>
</p>
<p align="center">
  <b>支付宝</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <b>微信支付</b>
</p>

---

<p align="center">
  Made with ❤️ using Flutter
</p>
