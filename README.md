# 🚀 SpigotMC-AutoBuild

> 自动化构建多版本 Spigot Jar 并一键发布 Release！  
> Powered by GitHub Actions ✨

---

## 📝 项目简介

本仓库通过 GitHub Actions 实现了 Spigot 多版本自动编译、校验、打包和发布 Release 的全流程自动化。  
只需等待定时任务或手动触发，所有主流 Spigot 版本的 Jar 及 SHA256 校验文件都会自动生成并上传到 Release，极大提升你的开发与部署效率！

---

## 🎯 功能特性

- ⏰ **每日自动构建**（北京时间早上8点）
- 🖱️ **支持手动触发**
- 🏗️ **多版本 Spigot 一键编译**
- 🔐 **自动生成 SHA256 校验文件**
- 📦 **所有产物自动上传到 Release**
- 📝 **Release 自动生成详细版本列表**
- ⭐ **开箱即用，零配置，持续维护**

---

## 🛠️ 支持的 Spigot 版本

- 1.8.8
- 1.12.2
- 1.16.5
- 1.17.1
- 1.18.2
- 1.19.4
- 1.20.6
- 1.21
- 1.21.1
- 1.21.3
- 1.21.4
- 1.21.5

---

## 🚦 使用方式

### 1. 自动定时构建

无需任何操作，每天早上8点（UTC 0点）自动构建并发布最新 Release。

### 2. 手动触发构建

1. 进入 GitHub 仓库页面
2. 点击 `Actions` → 选择 `Spigot 多版本自动构建`
3. 点击右侧 `Run workflow` 按钮即可立即触发

---

## 📥 下载方式

- 进入 [Releases](https://github.com/dm192/SpigotMC-AutoBuild/releases) 页面
- 点击最新的 Release，下载你需要的 Spigot Jar 及对应的 `.sha256` 校验文件

---

## 🔒 校验文件说明

每个 Jar 文件都配有同名 `.sha256` 校验文件，下载后可用如下命令校验完整性：

```bash
sha256sum -c spigot-1.20.6.jar.sha256
```

---

## 🤝 贡献与反馈

- 欢迎提交 Issue 或 PR 参与改进！
- 有任何建议或问题请在 [Issues](https://github.com/dm192/SpigotMC-AutoBuild/issues) 区留言

---

## ⭐ 支持一下

如果你觉得本项目有用，欢迎点个 Star！  
你的支持是我们持续维护的最大动力！🌟

---

> **Made with ❤️ by [dm192](https://github.com/dm192) & Contributors**