# CEAI 移动端 AI 决策原型

Mobile AI decision flow prototype for CEAI Library — 移动端优先的 AI 选机助手原型。

## 🚀 在线预览

**GitHub Pages:** https://markjinli.github.io/ceai-mobile-ai-decision-preview/

## 简介

CEAI 选机助手是一款面向手机端的 AI 笔记本电脑推荐工具原型，核心功能包括：

- **持久化候选面板** — 始终可见的筛选项看板（例如："已从 180 台筛到 24 台"）
- **AI 对话引擎** — 用户通过自然语言描述需求，AI 逐步推荐（预算、用途、便携性等）
- **结果对比页** — 多 Tab 切换（首选 / 备选 / 收藏 / 终轮对比），支持最多 4 台笔记本横向对比
- **交互式筛选** — 收藏、对比、查看关键差异（重量/性能/风险）

## 技术栈

纯前端静态页面，可直接部署到 GitHub Pages。

- HTML5 + CSS3
- 响应式移动端设计

## 本地运行

直接用浏览器打开 `index.html`，或使用任意静态文件服务器：

```bash
python -m http.server 8000
```

```bash
npx serve .
```

然后访问 `http://localhost:8000`
