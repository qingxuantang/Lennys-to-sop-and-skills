# Lenny's Podcast SOP Library

[English](#english) | [中文](#中文)

---

<a name="english"></a>
## English

> <blockquote class="twitter-tweet"><p lang="en" dir="ltr">Here are the full transcripts from all 320 of my podcast episodes.<br><br>It&#39;s been super fun for me to play with AI to extract insights from this data. Now you can to.<br><br>My only ask is that if you do something cool with it, just let me know.<br><br>I&#39;ll keep this folder updated with as each…</p>&mdash; Lenny Rachitsky (@lennysan) <a href="https://twitter.com/lennysan/status/2011243567340298651?ref_src=twsrc%5Etfw">January 14, 2026</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### Overview

A curated collection of **Standard Operating Procedures (SOPs)** extracted from [Lenny's Podcast](https://www.lennyspodcast.com/) - the #1 podcast for product management and growth. These SOPs transform expert insights into actionable frameworks you can apply immediately.

> **Current Status**: Tier 1-3 Complete (225 SOPs / 9 Claude Skills)
> Final extraction phase complete. Additional transcripts may be processed in future updates.

### What's Included

#### SOPs vs Skills: When to Use Each

| Format | Best For | Use Case |
|--------|----------|----------|
| **SOPs** (`/sops`) | Deep learning & long-form content | Writing articles, creating training materials, teaching frameworks in-depth, or when you need the full context and methodology |
| **Skills** (`/skills`) | Quick reference & AI integration | Real-time decision support, getting instant recommendations, when you need fast actionable guidance during work |

**Example**: Use the SPADE SOP when writing a blog post about decision frameworks. Use `/decision-maker` skill when you're in a meeting and need quick guidance on structuring a decision.

---

#### 9 Claude Code Skills

These skills bundle related SOPs for easy access. Use them in [Claude Code](https://claude.ai/claude-code) by typing the skill name:

| Skill | Description | Frameworks |
|-------|-------------|------------|
| `/decision-maker` | High-stakes decision making | SPADE, Nominal Group, Kill Criteria, Pre-Mortem, Opportunity Cost |
| `/pm-coach` | PM skill development | PM Competencies, Product Sense, Three Levels, High Agency, Design Feedback, Product Reviews |
| `/strategy-advisor` | Product & business strategy | Product Strategy Stack, DHM, Seven Powers, Execution vs Strategy |
| `/growth-advisor` | Growth and scaling | Adjacent User, Understand Work, Kindle Fire, Platform Cycles, Data Network Effects, PLG |
| `/leadership-coach` | Leadership & management | Radical Candor, Selective Micromanagement, Managing Complex Change, Bloom's Taxonomy, Coaching Tree, Career Impact |
| `/goal-setter` | Goals & prioritization | NCT Goal Setting, GEM Prioritization, LNO Time Management |
| `/hiring-guide` | Hiring PMs and leaders | First PM Hiring, Hiring Leaders, PM Competencies for interviews |
| `/gtm-advisor` | Go-to-market strategy | Champion Persona, Five Component Positioning, JTBD, Four Forces, Willingness to Pay |
| `/sop-library` | Browse all 225 SOPs | Master index by domain, situation, and source |

**Note:** The 9 skills are domain bundles, not individual SOP wrappers. This was an intentional design decision from the original plan. The 9 domain categories (decision-maker, pm-coach, strategy-advisor, growth-advisor, leadership-coach, goal-setter, hiring-guide, gtm-advisor, sop-library) comprehensively cover all content from Lenny's Podcast. New SOPs get added to the appropriate existing skill rather than creating new skill categories.

Example: When we extracted 40+ leadership SOPs, they all enriched /leadership-coach with new sections (Founder Mode, Emotional Intelligence, Culture Building, etc.) rather than creating /founder-mode-skill, /emotional-intelligence-skill, etc.

#### 225 SOPs by Domain

| Domain | Count | Key Frameworks |
|--------|-------|----------------|
| Leadership | 40+ | Radical Candor, Founder Mode, Engineering Management, Culture |
| Growth | 40+ | Adjacent User Theory, PLG, Marketplaces, Virality |
| PM Skills | 20+ | PM Competencies, Product Sense, High Agency, AI-Era PM |
| Product Strategy | 20+ | Strategy Stack, DHM, Seven Powers, AI Strategy |
| Go-to-Market | 8+ | JTBD, Positioning, Developer Tools, Technical Marketing |
| Sales | 8 | Founder-Led Sales, B2B Playbook, Enterprise Sales |
| Pricing | 5 | SaaS Pricing, Value Metrics, Willingness to Pay |
| Discovery | 15+ | Lean MVP, Design Sprint, PMF Measurement |
| Goals & Prioritization | 10+ | OKRs, NCT, GEM, LNO, Pre-Mortem |
| Decision Making | 4 | SPADE, Nominal Group, Kill Criteria, Pivot |
| Communication | 11 | Presentations, Public Speaking, Executive Comm |
| Hiring | 3 | First PM, Hiring Leaders, PM Intangibles |
| Behavioral Design | 4 | Three Bs, Friction Audit, Defaults |
| Roadmapping | 4 | Now-Next-Later, Stakeholder Alignment |
| Delivery | 5 | Shape Up, Six-Week Cycles, Hill Charts |

#### Expert Sources (20+)

- **Bangaly Kaba** (Instagram, Instacart) - 7 SOPs
- **Shreyas Doshi** (Stripe, Twitter) - 7 SOPs
- **Ravi Mehta** (Tinder, Facebook) - 4 SOPs
- **Casey Winters** (Pinterest, Grubhub) - 4 SOPs
- **April Dunford** (Positioning Expert) - 2 SOPs
- **Gokul Rajaram** (Square, DoorDash) - 3 SOPs
- **Gibson Biddle** (Netflix) - 2 SOPs
- **Julie Zhuo** (Facebook) - 2 SOPs
- **Bob Moesta** (JTBD Creator) - 2 SOPs
- And more...

### Project Structure

```
.
├── skills/                  # 9 Claude Code skills
│   ├── decision-maker/
│   ├── pm-coach/
│   ├── strategy-advisor/
│   ├── growth-advisor/
│   ├── leadership-coach/
│   ├── goal-setter/
│   ├── hiring-guide/
│   ├── gtm-advisor/
│   └── sop-library/
├── sops/                    # 52 detailed SOP files
│   ├── decision-making/
│   ├── leadership/
│   ├── product-management/
│   ├── growth/
│   ├── hiring/
│   ├── communication/
│   ├── go-to-market/
│   ├── positioning/
│   ├── customer-research/
│   ├── pricing/
│   ├── strategy/
│   ├── experimentation/
│   └── personal-development/
├── docs/
│   ├── sop-index.md         # Complete SOP index
│   └── sop-to-skills-plan.md
└── README.md
```

### How to Use

#### Option 1: Claude Code Skills (Recommended)

1. Clone this repo
2. Copy the `skills/` folder to your project's `.claude/skills/` directory:
   ```bash
   cp -r skills/ your-project/.claude/skills/
   ```
3. Open your project with Claude Code
4. Type a skill name like `/decision-maker` or ask a question like "How do I prioritize features?"
5. Claude will automatically apply the relevant frameworks

#### Option 2: Direct SOP Access

Browse the `/sops` directory for detailed step-by-step procedures. Each SOP includes:
- Source and context
- When to use
- Step-by-step procedure
- Templates and examples
- Pitfalls to avoid

### Progress & Roadmap

| Phase | Status | Description |
|-------|--------|-------------|
| Tier 1 | ✅ Complete | High-impact transcripts (20 episodes) → 35 SOPs |
| Tier 2 | ✅ Complete | Important transcripts (30 episodes) → 17 SOPs |
| Tier 3 | ✅ Complete | Additional expert transcripts (80+ episodes) → 173 SOPs |
| Tier 4 | ⏳ Future | Remaining transcripts for community contribution |

**Current Total**: 225 SOPs from 80+ expert sources

### Contributing

Contributions welcome! See our extraction methodology in `/docs/sop-to-skills-plan.md`.

### License

This project extracts and organizes publicly available podcast content for educational purposes. All frameworks are attributed to their original sources.

---

<a name="中文"></a>
## 中文

> <blockquote class="twitter-tweet"><p lang="en" dir="ltr">Here are the full transcripts from all 320 of my podcast episodes.<br><br>It&#39;s been super fun for me to play with AI to extract insights from this data. Now you can to.<br><br>My only ask is that if you do something cool with it, just let me know.<br><br>I&#39;ll keep this folder updated with as each…</p>&mdash; Lenny Rachitsky (@lennysan) <a href="https://twitter.com/lennysan/status/2011243567340298651?ref_src=twsrc%5Etfw">January 14, 2026</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### 项目概述

这是一个从 [Lenny's Podcast](https://www.lennyspodcast.com/)（产品管理和增长领域排名第一的播客）中提取的**标准操作程序（SOP）**合集。这些 SOP 将专家洞见转化为可立即应用的实用框架。

> **当前状态**：Tier 1-3 已完成（225 个 SOP / 9 个 Claude 技能）
> 提取阶段已完成。后续可能处理更多播客。

### 包含内容

#### SOP 与 Skills 的区别：何时使用

| 格式 | 最适合 | 使用场景 |
|------|--------|----------|
| **SOP** (`/sops`) | 深度学习和长篇内容 | 撰写文章、创建培训材料、深入讲解框架，或当你需要完整的背景和方法论时 |
| **Skills** (`/skills`) | 快速参考和 AI 集成 | 实时决策支持、获取即时建议、工作中需要快速可执行指导时 |

**示例**：撰写关于决策框架的博客文章时使用 SPADE SOP；在会议中需要快速了解如何构建决策时使用 `/decision-maker` 技能。

---

#### 9 个 Claude Code 技能

这些技能将相关 SOP 打包以便快速访问。在 [Claude Code](https://claude.ai/claude-code) 中输入技能名称即可使用：

| 技能 | 描述 | 包含框架 |
|------|------|----------|
| `/decision-maker` | 高风险决策 | SPADE、名义小组法、终止标准、事前验尸、机会成本 |
| `/pm-coach` | PM 技能发展 | PM 能力模型、产品感觉、三层工作法、高主动性、设计反馈、产品评审 |
| `/strategy-advisor` | 产品与业务战略 | 产品战略栈、DHM、七种力量、执行vs战略 |
| `/growth-advisor` | 增长与扩展 | 相邻用户理论、理解工作框架、Kindle Fire、平台周期、数据网络效应、PLG |
| `/leadership-coach` | 领导力与管理 | 彻底坦诚、选择性微观管理、管理复杂变革、布鲁姆分类法、教练树、职业影响力 |
| `/goal-setter` | 目标与优先级 | NCT 目标设定、GEM 优先级排序、LNO 时间管理 |
| `/hiring-guide` | 招聘 PM 和领导者 | 首位 PM 招聘、招聘领导者、面试能力评估 |
| `/gtm-advisor` | 上市策略 | 支持者画像、五要素定位、JTBD、四种力量、支付意愿研究 |
| `/sop-library` | 浏览全部 225 个 SOP | 按领域、场景、来源索引 |

**说明：** 这 9 个技能是按领域打包的，而不是每个 SOP 单独一个技能。这是原始设计方案中的刻意决定。这 9 个领域类别（decision-maker、pm-coach、strategy-advisor、growth-advisor、leadership-coach、goal-setter、hiring-guide、gtm-advisor、sop-library）全面覆盖了 Lenny's Podcast 的所有内容。新的 SOP 会被添加到相应的现有技能中，而不是创建新的技能类别。

示例：当我们提取了 40+ 个领导力 SOP 时，它们都被整合到 /leadership-coach 中，增加了新的章节（创始人模式、情商、文化建设等），而不是创建 /founder-mode-skill、/emotional-intelligence-skill 等单独的技能。

#### 225 个 SOP（按领域分类）

| 领域 | 数量 | 核心框架 |
|------|------|----------|
| 领导力 | 40+ | 彻底坦诚、创始人模式、工程管理、文化 |
| 增长 | 40+ | 相邻用户理论、PLG、市场平台、病毒传播 |
| PM 技能 | 20+ | PM 能力模型、产品感觉、高主动性、AI 时代 PM |
| 产品战略 | 20+ | 战略栈、DHM、七种力量、AI 战略 |
| 上市策略 | 8+ | JTBD、定位、开发者工具、技术营销 |
| 销售 | 8 | 创始人销售、B2B 销售手册、企业销售 |
| 定价 | 5 | SaaS 定价、价值指标、支付意愿 |
| 发现 | 15+ | 精益 MVP、设计冲刺、PMF 测量 |
| 目标与优先级 | 10+ | OKR、NCT、GEM、LNO、事前验尸 |
| 决策 | 4 | SPADE、名义小组法、终止标准、转型 |
| 沟通 | 11 | 演讲、公开演讲、高管沟通 |
| 招聘 | 3 | 首位 PM、招聘领导者、PM 软技能 |
| 行为设计 | 4 | 三B框架、摩擦审计、默认值 |
| 路线图 | 4 | Now-Next-Later、利益相关者对齐 |
| 交付 | 5 | Shape Up、六周周期、Hill Charts |

#### 专家来源（20+位）

- **Bangaly Kaba**（Instagram、Instacart）- 7 个 SOP
- **Shreyas Doshi**（Stripe、Twitter）- 7 个 SOP
- **Ravi Mehta**（Tinder、Facebook）- 4 个 SOP
- **Casey Winters**（Pinterest、Grubhub）- 4 个 SOP
- **April Dunford**（定位专家）- 2 个 SOP
- **Gokul Rajaram**（Square、DoorDash）- 3 个 SOP
- **Gibson Biddle**（Netflix）- 2 个 SOP
- **Julie Zhuo**（Facebook）- 2 个 SOP
- **Bob Moesta**（JTBD 创始人）- 2 个 SOP
- 更多...

### 项目结构

```
.
├── skills/                  # 9 个 Claude Code 技能
│   ├── decision-maker/
│   ├── pm-coach/
│   ├── strategy-advisor/
│   ├── growth-advisor/
│   ├── leadership-coach/
│   ├── goal-setter/
│   ├── hiring-guide/
│   ├── gtm-advisor/
│   └── sop-library/
├── sops/                    # 52 个详细 SOP 文件
│   ├── decision-making/
│   ├── leadership/
│   ├── product-management/
│   ├── growth/
│   ├── hiring/
│   ├── communication/
│   ├── go-to-market/
│   ├── positioning/
│   ├── customer-research/
│   ├── pricing/
│   ├── strategy/
│   ├── experimentation/
│   └── personal-development/
├── docs/
│   ├── sop-index.md         # 完整 SOP 索引
│   └── sop-to-skills-plan.md
└── README.md
```

### 使用方法

#### 方式一：Claude Code 技能（推荐）

1. 克隆此仓库
2. 将 `skills/` 文件夹复制到你项目的 `.claude/skills/` 目录：
   ```bash
   cp -r skills/ your-project/.claude/skills/
   ```
3. 用 Claude Code 打开你的项目
4. 输入技能名称如 `/decision-maker` 或提问如"如何排列功能优先级？"
5. Claude 会自动应用相关框架

#### 方式二：直接访问 SOP

浏览 `/sops` 目录获取详细步骤。每个 SOP 包含：
- 来源和背景
- 适用场景
- 分步操作流程
- 模板和示例
- 常见陷阱

### 进度与路线图

| 阶段 | 状态 | 描述 |
|------|------|------|
| Tier 1 | ✅ 完成 | 高影响力播客（20 期）→ 35 个 SOP |
| Tier 2 | ✅ 完成 | 重要播客（30 期）→ 17 个 SOP |
| Tier 3 | ✅ 完成 | 额外专家播客（80+ 期）→ 173 个 SOP |
| Tier 4 | ⏳ 未来 | 剩余播客供社区贡献 |

**当前总计**：来自 80+ 位专家的 225 个 SOP

### 贡献

欢迎贡献！提取方法详见 `/docs/sop-to-skills-plan.md`。

### 许可

本项目出于教育目的整理公开播客内容。所有框架均注明原始来源。

---

<p align="center">
  <b>Built with insights from Lenny's Podcast | 基于 Lenny's Podcast 构建</b><br>
  <i>Transforming expert knowledge into actionable frameworks</i><br>
  <i>将专家知识转化为可执行框架</i>
</p>
