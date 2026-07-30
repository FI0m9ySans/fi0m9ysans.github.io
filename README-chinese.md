# 🍅 番茄时钟 · 模组版

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://FI0m9ySans.github.io/)
[![Issues](https://img.shields.io/github/issues/FI0m9ySans/fi0m9ysans.github.io)](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

> 一款功能齐全的番茄钟，支持**模组**、**模组市场**、**任务系统**以及**多语言切换**——一切都在您的浏览器中完成。

## 🌐 在线演示

**👉 [https://FI0m9ySans.github.io/](https://FI0m9ySans.github.io/)**

无需安装。所有数据均存储在您的浏览器本地。

---

## ✨ 功能特性

| 功能 | 描述 |
|---------|-------------|
| ⏱️ **番茄钟** | 专注 25 分钟即可赚取番茄币和经验值 |
| 🛒 **商店** | 购买“休息+5分钟”、“专注加成”、“盲盒”等物品 |
| 🎒 **背包** | 管理并使用您购买的物品 |
| 📋 **任务系统** | 创建带有奖励条件的任务（番茄币、经验值、物品、盲盒） |
| 🧩 **模组系统** | 导入/导出 `.shom`/`.shem`/`.zid`/`.zod`/`.taem` 文件 |
| 🌐 **模组市场** | 浏览并安装全球社区分享的模组 |
| 🌍 **双语支持** | 即时切换中文与英文 |
| 💾 **存档系统** | 将完整进度导出为 `.saop` 文件以备备份 |

---

## 📦 模组系统（文件格式）

| 扩展名 | 包含内容 | 描述 |
|-----------|---------|-------------|
| `.shom` | 物品 + 背包 | **推荐**用于物品模组 |
| `.shem` | 物品 + 背包 | 旧版格式（完全兼容） |
| `.zid` | 物品 + 任务 + 自定义标签页 | **推荐**用于完整模组 |
| `.zod` | 物品 + 任务 + 自定义标签页 | 旧版格式（完全兼容） |
| `.taem` | 仅任务 | 分享任务列表 |
| `.saop` | 完整存档数据 | 备份您的进度 |

---

## 🧩 模组市场与贡献

本仓库同时也是一个**全局模组数据库**。任何人都可以提交自己的模组！

### 📤 提交您的模组

1. 点击 **[新建 Issue](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues/new/choose)**
2. 选择您偏好的语言模板（中文 / 英文）
3. 填写模组详细信息并提交
4. 审核通过后，您的模组将出现在应用内的**模组市场**中

### 📂 文件结构

```text
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

# 直接在浏览器中打开 index.html
# 或者使用 Live Server (VS Code) 以获得更好的体验
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

欢迎参与贡献！您可以通过以下方式提供帮助：

- 🧩 **提交模组** → 使用 [Issue 模板](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues/new/choose)
- 🐛 **报告 Bug** → [新建 Issue](https://github.com/FI0m9ySans/fi0m9ysans.github.io/issues)
- 💡 **建议新功能** → 发起 Discussion 或 Issue

---

## 📜 许可证

MIT 许可证 —— 自由使用、修改和分享。

---

## 📧 联系方式

- GitHub: [@FI0m9ySans](https://github.com/FI0m9ySans)
- Discord 服务器: [@FI0m9ySans 的社区中心](https://discord.gg/Kxp3KGBJr8)
- 邮箱: fi0m9ysans@foxmail.com

---

**🍅 让专注再次充满乐趣！**
