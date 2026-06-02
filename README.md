# AI 协作实践心得

作者：**吕韧**

个人关于 AI 时代如何与模型和工具长期协作的实践总结，涵盖认知、策略、工程方法与文档沉淀。

> **文档迭代：第 9 次修订**（[Git 记录](https://github.com/reason515/ai-using/commits/main)）· 最近更新：2026-05-27  
> 这份文档本身即是「持续迭代」的样例——每一次修订，都来自实际使用后的总结与反思。

## 在线阅读

- **GitHub Pages（推荐）**：部署 `index.html` 后访问站点首页
- 本地预览：用浏览器直接打开 [index.html](./index.html)

## 仓库文件

| 文件 | 说明 |
|------|------|
| [index.html](./index.html) | GitHub Pages 展示页（响应式，桌面/移动端） |
| [doc-meta.json](./doc-meta.json) | 文档迭代次数与更新日期（改文档后请同步 +1） |
| [AI使用心得-PPT大纲.md](./AI使用心得-PPT大纲.md) | 完整大纲与精炼文案 |
| [AI使用心得-分享版.html](./AI使用心得-分享版.html) | 适合打印/导出 PDF 的文档版 |
| [AI使用心得.html](./AI使用心得.html) | Reveal.js 幻灯片（现场演示） |

## 启用 GitHub Pages

1. 进入仓库 **Settings → Pages**
2. **Source** 选择 `Deploy from a branch`
3. **Branch** 选 `main`，目录选 `/ (root)`
4. 保存后访问：`https://reason515.github.io/ai-using/`

## 核心观点摘要

- 工具会变，底层逻辑（拆解、验证、复盘）不会变
- 任务的主体是人：你告诉 AI 做什么，而不是问 AI 你该做什么
- 把实现细节交给 AI，把注意力留给高价值决策
- 复杂项目：Sprint 节奏 + 实例化需求 + TDD
- AI 会偷懒：认真检查 vs 几乎不检查，质量天上地下；懒人用不好 AI，常因少想也少验
- 不懂开发也建议学 Git：代码和文档都要版本管理，AI Agent 的 bug 无法完全避免
- Rules / Skills 能提效提质，但须自己先理解，并通过有意识的多用来加深
- 新概念新工具层出不穷：结合自身选择性采用，不盲目跟风
- 一切经验文档化，用 Markdown 与 Mermaid 连接人与 AI
