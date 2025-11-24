
# 🗺️ Public Economics Research Roadmap | 财政学研究图谱

![Status](https://img.shields.io/badge/Status-Active-brightgreen) ![Discipline](https://img.shields.io/badge/Field-Public_Economics-blue) ![Tool](https://img.shields.io/badge/Built_with-Obsidian-purple)

> **A collaborative knowledge graph connecting classic questions, frontier literature, and research gaps.**
> 一个协作式的学科知识图谱：连接经典问题、前沿文献与待解决的研究空白。

---

## 📖 关于本项目 (About)

本项目旨在构建一个**结构化的财政学/公共经济学研究路线图**。我们不以“作者”为中心，而是以**“研究问题 (Research Questions)”**为核心节点，记录理论演进与实证前沿。

**核心目标：**
1.  **Mapping:** 梳理本领域的核心问题树（如税收、支出等）。
2.  **Tracking:** 追踪最新的文献进展与实证发现。
3.  **Identifying Gaps:** 明确当前的未解之谜与政策痛点 (Research Gaps)。

## 🗂️ 目录结构 (Directory Structure)

本项目采用清晰的模块化设计，当前结构如下：

```text
PublicEcon-Roadmap/
├── 00_Index/
│   └── Roadmap_Overview.md    # [总控台] 全局仪表盘与导航索引
│
├── 10_Problem_Set/            # [核心] 研究问题库 (按子领域分类)
│   ├── Taxation/              # 税收理论与政策 (e.g. 最优所得税)
│   ├── Public Expenditure/    # 公共支出分析
│   └── ...
│
├── 20_Literature_Notes/       # [支撑] 文献精读卡片
│   └── Author_Year_Title.md   # (e.g. Diamond_1998_Optimal_Income_Tax)
│
├── 99_Templates/              # [规范] 贡献者必用的标准化模板
│   ├── Template_研究问题.md
│   └── Template_文献卡片.md
│
├── Assets/                    # 图片与静态资源
└── README.md                  # 项目说明书
```
## 🚀 如何参与贡献 (Contribution Guide)

非常欢迎提交 Pull Request 来丰富这个图谱！请遵循以下工作流：

### 1. 添加一个新的“研究问题”

- **位置**: 根据主题存入 `10_Problem_Set/` 下的对应文件夹（如 `Taxation`）。
- **模板**: 必须应用 `99_Templates/Template_研究问题` 模板。
- **内容**: 重点描述该问题的核心矛盾、经典理论来源以及当下的研究空白。

### 2. 添加一篇“文献笔记”

- **位置**: 存入 `20_Literature_Notes/` 文件夹。
- **命名**: 建议格式 `Author_Year_Keywords.md` (如 `Chetty_2014_Active_Decisions`)。
- **模板**: 必须应用 `99_Templates/Template_文献卡片` 模板。
- **关联**: 请务必在笔记中通过双向链接 `[[...]]` 引用它解决的那个研究问题。

### 3. 常用标签 (Tags)

我们在笔记头部的 Frontmatter 中使用以下标签来标记状态：

- `#Open_Question`: 尚无定论的开放性问题
- `#Solved`: 理论框架已基本成熟
- `#Urgent_Policy`: 现实政策急需回应的问题

---

## ⚠️ 许可说明

文献 PDF 原文请自行获取，不直接存储于本仓库。


