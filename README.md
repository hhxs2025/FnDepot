# fnos-fpk 飞牛 fnOS 应用打包仓库

本仓库包含多个为飞牛 fnOS 开发的 Native 应用源码和打包文件（.fpk）。

所有应用均为独立开发的第三方应用，遵循 MIT 开源协议。

---

## 📦 应用列表

| 应用 | 版本 | 状态 | 源码目录 | fpk 下载 |
|------|------|------|----------|----------|
| 文件收集助手 | v1.0.0 | ✅ 可用 | [/file-collector](./file-collector) | [下载](https://gitee.com/你的用户名/fnos-fpk/releases/download/v1.0.0/file-collector-1.0.0.fpk) |
| 物价系统 | v1.0.0 | ✅ 可用 | [/price-system](./price-system) | [下载](https://gitee.com/你的用户名/fnos-fpk/releases/download/v1.0.0/price-system-1.0.0.fpk) |

---

## 📖 各应用详情

### 📂 文件收集助手

一键收集团队成员文件，支持创建收集任务、文件上传、二维码分享。

- **源码目录**：[file-collector/](./file-collector)
- **技术栈**：Flask + TinyDB + qrcode
- **默认账号**：admin / admin123
- **详细说明**：[查看 README](./file-collector/README.md)

### 📊 物价系统

记录商品价格，智能比价，帮你找到最划算的购买渠道。

- **源码目录**：[price-system/](./price-system)
- **技术栈**：Flask + SQLite
- **默认账号**：admin / admin123
- **详细说明**：[查看 README](./price-system/README.md)

---

## 📥 安装方式

1. 下载对应应用的 `.fpk` 文件
2. 登录飞牛 fnOS → 应用中心 → 手动安装
3. 选择 `.fpk` 文件，按向导完成安装

---

## 📝 更新日志

### v1.0.0 (2026-06-23)

- 首次发布
- 文件收集助手：支持创建任务、文件上传、二维码分享
- 物价系统：支持商品管理、价格记录、智能比价

---

## 📄 开源协议

MIT License

---

## 👨‍💻 开发者

晦华先生 · 2303537063@qq.com
