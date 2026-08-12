# 知识星图 · Knowledge Galaxy

市场研发中心 Obsidian vault 的知识图谱可视化页面。

## 数据来源

扫描自 `F:\市场研发中心` vault，2026-08-12 抓取，**仅含 5 个业务目录**：
- 01 产研+实验室（438 笔记）
- 02 品牌部（157 笔记）
- 03 市场客源组（137 笔记）
- 04 市场内容组（56 笔记）
- 00 中心（12 笔记）

合计 **800 笔记 / 1067 条 wikilink 边**。

## 部署

GitHub Pages 公开部署，URL：
**https://yvette5627.github.io/knowledge-galaxy/**

## 文件

- `galaxy-view.html` — 渲染壳（HTML + CSS + 力导向 + 交互）
- `galaxy-data.js` — 节点 + 边数据（`window.__GALAXY_DATA__`）
- 旧版归档在 `D:\Hermes工作区\galaxy-view版本归档\`

## 交互

- 鼠标悬停节点 → 显示文件名 + 目录 + 连接数
- 单击节点 → 聚焦，顶部显示该节点详情
- 双击节点 → 打开 vault 里的真实文件（仅本机有效）
- 滚轮缩放 / 拖拽节点 / 拖拽空白平移
