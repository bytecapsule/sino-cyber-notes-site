# sino-cyber-notes-site

赛博笔记文档站 — 基于 [sino-cyber-notes](https://github.com/bytecapsule/sino-cyber-notes) 原始 TXT 数据，转换为 Markdown 后通过 MkDocs + GitHub Pages 发布。

## 架构

- **数据源：** `bytecapsule/sino-cyber-notes`（原始 TXT 文件）
- **本站：** Markdown 格式归档 + MkDocs Material 主题
- **发布：** GitHub Pages（`gh-pages` 分支，Actions 自动构建）

## 本地开发

```bash
pip install mkdocs-material
mkdocs serve
```

## 部署

Push 到 `main` 分支后，GitHub Actions 自动构建并发布到 GitHub Pages。
