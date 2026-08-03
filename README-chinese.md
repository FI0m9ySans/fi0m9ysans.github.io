# 🍅 番茄闹钟 · 模组版

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://FI0m9ySans.github.io/)
[![Issues](https://img.shields.io/github/issues/FI0m9ySans/fi0m9ysans.github.io)](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

> 一个功能完整的番茄钟工具，支持**模组系统**、**模组市场**、**任务系统**和**多语言** —— 全在浏览器中运行。

## 🌐 在线演示

**👉 [https://FI0m9ySans.github.io/](https://FI0m9ySans.github.io/)**

无需安装，所有数据存储在浏览器本地。

---

## ✨ 功能特性

| 功能 | 说明 |
|------|------|
| ⏱️ **番茄计时** | 专注 25 分钟，赚取番茄币和经验值 |
| 🛒 **商店** | 购买“休息+5分钟”、“专注加成”、“开箱”等道具 |
| 🎒 **背包** | 管理和使用已购买的道具 |
| 📋 **任务系统** | 创建带有奖励条件（番茄币、经验、物品、开箱）的任务 |
| 🧩 **模组系统** | 导入/导出 `.tomod`、`.shom`、`.shem`、`.zid`、`.zod`、`.taem` 文件 |
| 🌐 **模组市场** | 浏览并安装全球社区分享的模组 |
| 🌍 **双语支持** | 一键切换中英文 |
| 💾 **存档系统** | 导出完整进度为 `.saop` 文件，用于备份 |

---

## 📦 模组系统（文件格式）

| 扩展名 | 包含内容 | 说明 |
|--------|----------|------|
| **`.tomod`** | 物品 + 任务 + 自定义标签页 + 脚本 + 页面 | **推荐**完整模组格式（基于 ZIP，支持 JS 和 HTML） |
| `.shom` | 物品 + 背包 | 推荐纯物品模组 |
| `.shem` | 物品 + 背包 | 旧版格式（完全兼容） |
| `.zid` | 物品 + 任务 + 自定义标签页 | 旧版格式（完全兼容） |
| `.zod` | 物品 + 任务 + 自定义标签页 | 旧版格式（完全兼容） |
| `.taem` | 仅任务 | 分享任务清单 |
| `.saop` | 完整存档数据 | 备份你的进度 |

> **注意：** `.tomod` 是目前推荐的格式，支持自定义脚本、页面以及所有模组功能，一个文件搞定全部。

---

## 🧩 模组市场与贡献

本仓库同时也是**全球模组数据库**。任何人都可以提交自己的模组！

### 📤 提交模组

1. 点击 **[新建 Issue](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues/new/choose)**
2. 选择你偏好的语言模板（中文 / English）
3. 填写模组详细信息（名称、描述、文件链接、标签等）
4. 提交 —— 审核通过后，你的模组会出现在应用内的 **模组市场** 中

### 📂 文件结构

```
fi0m9ysans.github.io/
├── index.html          # 主程序
├── mods.json           # 模组索引（应用自动加载）
├── mods/               # 模组文件目录
│   ├── xbox_controller.shom
│   └── ...
└── .github/
    └── ISSUE_TEMPLATE/
        ├── mod-submission-zh.yml
        └── mod-submission-en.yml
```

---

## 🚀 本地运行

```bash
# 克隆仓库
git clone https://github.com/FI0m9ySans/fi0m9ysans.github.io.git

# 直接用浏览器打开 index.html
# 或使用 VS Code 的 Live Server 获得更好体验
```

---

## 🛠️ 技术栈

- **前端**：原生 HTML + CSS + JavaScript
- **图标**：FontAwesome
- **存储**：localStorage（无需服务器）
- **托管**：GitHub Pages
- **模组提交**：GitHub Issues

---

## 🤝 参与贡献

欢迎各种形式的贡献！你可以通过以下方式帮助我们：

- 🧩 **提交模组** → 使用 [Issue 模板](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues/new/choose)
- 🐛 **报告 Bug** → [新建 Issue](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues)
- 💡 **提出建议** → 发起讨论或新建 Issue

---

## 📜 许可证

MIT 许可证 —— 免费使用、修改和分享。

---

## 📧 联系我

- GitHub: [@FI0m9ySans](https://github.com/FI0m9ySans)
- Discord 服务器: [@FI0m9ySans's Community Hub](https://discord.gg/Kxp3KGBJr8)
- 邮箱: fi0m9ysans@foxmail.com

---

**🍅 让专注变得更有趣！**
