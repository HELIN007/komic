# Komic - 多源漫画阅读器

<p align="center">
  <img src="assets/logo.png" alt="Komic Logo" width="120"/>
</p>

<p align="center">
  <b>在线 + 本地 | AI 画质增强</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/版本-1.2.7-blue" alt="Version"/>
  <img src="https://img.shields.io/badge/平台-Android-green" alt="Platform"/>
  <img src="https://img.shields.io/badge/Flutter-Dart-02569B?logo=flutter" alt="Flutter"/>
</p>

---

## 项目简介

Komic 是一个以「统一内容入口 + 沉浸式阅读体验」为核心的 Android 阅读应用。  
它不仅支持漫画阅读，也覆盖电子书、有声书、离线资料管理，以及多种数据源之间的统一浏览、搜索、下载与进度管理。

当前代码实现已经覆盖以下核心场景：

- 统一接入 `Komga`、`Kavita`、`WebDAV`、本地文件与 `Audiobookshelf`
- 提供书架、在读、听书、离线库、设置等主入口
- 支持漫画、电子书、有声书的差异化阅读与播放体验
- 支持本地下载、缓存管理、阅读统计、数据备份恢复
- 提供 AI 画质增强、白边裁切、双页拆分等增强能力

---

## 核心能力

### 多源内容接入

- `Komga`：浏览系列、书籍、封面与阅读进度
- `Kavita`：接入系列详情、书籍列表与阅读流程
- `WebDAV`：支持远程文件浏览、流式阅读与下载
- 本地文件：管理本地漫画目录与离线资源
- `Audiobookshelf`：接入有声书库、书籍详情、收藏、书签与下载

### 阅读与播放体验

- 漫画阅读：支持多方向、多翻页模式、点击热区自定义
- 电子书阅读：支持字体、排版、背景与阅读参数配置
- 有声书播放：支持播放控制、进度管理、书签与缓存
- 在读管理：统一展示最近阅读内容，方便快速续读

### 阅读增强

- 双页拆分
- 自动裁切白边
- 纸张纹理与阅读背景定制
- 页面预加载与性能优化
- AI 画质增强

当前项目内置的 AI 模型资源包含：

- `waifu2x-anime`
- `waifu2x-cunet`
- `real-cugan`

### 数据与存储

- 在线内容离线下载
- 下载队列与下载模式管理
- 图片裁切缓存与音频缓存管理
- 阅读统计
- 数据备份与恢复

### 应用级能力

- 激活码校验与设备激活流程
- 版本检查与应用更新提示
- 日志管理
- 权限管理
- 通知展示配置
- 外观、Tab、主题与安全设置

---

## 适用内容类型

Komic 当前实现主要围绕以下内容类型展开：

- 漫画 / 图像型阅读内容
- EPUB / PDF 等电子书内容
- 有声书内容
- 本地离线资料与下载资源

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
