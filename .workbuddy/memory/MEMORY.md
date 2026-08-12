# 项目记忆 · 个人工作台

## 关联仓库
- GitHub：`FI0m9ySans/fi0m9ysans.github.io`（GitHub Pages，分支 `main`）
- 工作台本地目录：`D:/empty_null_none/2026-08-13-04-40-42`

## 站点结构（部署后）
- `index.html` —— 个人工作台落地页（时钟/问候 + 待办/笔记/链接侧栏 + 内嵌番茄钟）
- `tomato.html` —— 原番茄钟 · Mod 版应用（由旧 `index.html` 改名保留，内联自包含）
- 番茄钟内嵌方式：工作台 `iframe src="tomato.html"`（同域，localStorage 共享）
- 番茄钟依赖外链：cdnjs font-awesome 6.4.0、jszip 3.10.1（需联网）

## 约定
- 改动后 `git push origin main` 即触发 GitHub Pages 部署
- 待办/笔记/链接数据存浏览器 localStorage（key: `wb_todos`/`wb_notes`/`wb_links`/`wb_theme`），不入库
