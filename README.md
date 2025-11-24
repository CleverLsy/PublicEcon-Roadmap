
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
│   ├── Taxation Theory & Structure/  # 税收理论与政策 (e.g. 最优所得税)
│   ├── Public Expenditure and Public Investment/    # 公共支出分析
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
---
## 🤝 零基础参与指南 (For Non-Coders)

不用担心弄坏代码，也不需要下载任何软件，您可以直接在网页上像“发帖子”一样参与贡献。我们提供两种模式：

### 🟢 模式一：路人模式 (提建议/纠错)

> 适用场景：发现文献年份写错了、推荐一篇新文章但不方便写笔记、或者对某个观点有疑问。

1. 点击本页面上方的 **[Issues]** 标签（只有圆圈图标的那个）。
2. 点击绿色的 **New Issue** 按钮。
3. 像在论坛发帖一样写下你的建议或发现的问题，点击 **Submit**。我们会尽快处理！

### 🔵 模式二：贡献者模式 (添加笔记)

> 适用场景：你写好了一篇新的文献笔记，或者整理了一个新的研究问题，想加入到图谱中。这就像**“交作业”**一样简单：

**步骤 1：复制仓库 (Fork)**  
点击页面右上角的 **Fork** 按钮。这相当于把这个项目“复印”了一份到你自己的账号下，那个是你自己的地盘，随便改。

**步骤 2：添加文件 (Add File)**

1. 在你自己的仓库页面里，进入 `20_Literature_Notes` (如果是文献) 文件夹。
2. 点击右上角的 `Add file` -> `Create new file`。
3. **文件名**填写：`作者_年份_标题关键词.md` (例如 `Saez_2010_Tax_Elasticity.md`)。
4. **内容**：最好先复制 `99_Templates` 里的模板内容，然后填入你的笔记。

**步骤 3：提交作业 (Pull Request)**

1. 写好后，点击页面底部的绿色 **Commit changes** 按钮保存。
2. 此时页面会有提示，点击 **Pull Request** (或者 **Contribute**) 按钮。
3. 再次确认点击 **Create Pull Request**。
4. 完成！这相当于你告诉管理员：“我写好了，请检查合并”。
---

## 📝 内容规范与录入指南 (Content Standards & Workflow)

为了保持 Public Econ Roadmap 知识图谱的连通性，所有新增内容请严格遵循以下规范。

### 1. 📂 文件归档位置 (File Location)

- **研究问题 (Topics/Problems)**
    - 存放于：`10_Problem_Set/` 下对应的子分类文件夹中。
    - *示例：* `10_Problem_Set/Taxation Theory & Structure/Optimal_Income_Tax.md`
- **文献笔记 (Literature Notes)**
    - 存放于：`20_Literature_Notes/` 文件夹。
    - *命名规范：* 使用 `Author_Year_Title` 格式（尽量扁平化，不要再建子文件夹）。
    - *示例：* `20_Literature_Notes/Saez_2001_Labor_Elasticity.md`

### 2. 📑 模板使用 (Templates)

请务必使用 `99_Templates/` 下的标准模板创建笔记，以保证 Frontmatter 元数据统一，确保网页能正确索引。

- 新增文献时 ➡️ 使用 `Template_Literature`
- 新增课题时 ➡️ 使用 `Template_Problem`

### 3. 🔗 核心动作：建立关联 (The Golden Rule of Linking)

**这是最重要的一步**。孤立的文献没有价值，必须将其挂载到具体的 **研究问题** 树上。

在创建文献笔记时，**必须** 在正文顶部包含指向 `10_Problem_Set` 的链接：

- **关联大类**：链接到子文件夹的 `index`。
    - *写法：* `所属领域: [[10_Problem_Set/Taxation Theory & Structure/index|🏛️ Taxation]]`
- **关联具体问题**：链接到具体的 `.md` 文件。
    - *写法：* `解决的核心问题: [[10_Problem_Set/Taxation Theory & Structure/Optimal_Taxation|🔑 最优税收理论]]`

> 💡 **为什么这么做？**
> 这样当你浏览“最优税收”的页面时，Quartz 的 Backlinks 功能会自动告诉你：“Saez (2001) 这篇论文关联了本话题”。

### 4. 🏷️ 常用状态标签 (Tags)

请在笔记开头的 `tags: [...]` 区域准确标记状态：

**对于研究问题 (in Problem Set):**
- `#Open_Question`: 尚无定论、值得深挖的开放性问题。
- `#Solved`: 理论框架已基本成熟，主要是回顾经典。
- `#Urgent_Policy`: 现实政策急需回应的问题（高优先级）。

**对于文献 (in Literature Notes):**
- `#Must_Read`: 该领域的奠基之作，必读。
- `#Empirical`: 实证类文章 (Data-driven)。
- `#Theoretical`: 理论模型类文章 (Model-driven)。

---
## ⚠️ 许可说明

文献 PDF 原文请自行获取，不直接存储于本仓库。


