# Lenny's Podcast SOP Library

[English](#english) | [中文](#中文)

---

<a name="english"></a>
## English

### Overview

A curated collection of **Standard Operating Procedures (SOPs)** extracted from [Lenny's Podcast](https://www.lennyspodcast.com/) - the #1 podcast for product management and growth. These SOPs transform expert insights into actionable frameworks you can apply immediately.

> **Current Status**: Tier 1 & 2 Complete (52 SOPs / 9 Claude Skills)
> Tier 3 & 4 in progress (~750-1,150 SOPs remaining from ~280 transcripts)

### What's Included

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
| `/sop-library` | Browse all 52 SOPs | Master index by domain, situation, and source |

#### 52 SOPs by Domain

| Domain | Count | Key Frameworks |
|--------|-------|----------------|
| Leadership | 9 | Radical Candor, Founder Mode, Company OS |
| Growth | 8+ | Adjacent User Theory, PLG, Kindle Fire |
| PM Skills | 7 | PM Competencies, Product Sense, High Agency |
| Product Strategy | 5 | Strategy Stack, DHM, Seven Powers |
| Go-to-Market | 5 | JTBD, Positioning, Willingness to Pay |
| Prioritization & Goals | 5 | NCT, GEM, LNO, Pre-Mortem |
| Decision Making | 3 | SPADE, Nominal Group, Kill Criteria |
| Discovery | 2 | Empowered Teams, Opportunity Solution Tree |
| Hiring | 2 | First PM, Hiring Leaders |
| Communication | 2 | Executive Communication, Metaphor Alignment |
| Other | 4 | A/B Testing, Independent Opinion |

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
| Tier 3 | 🔄 In Progress | Standard transcripts (~150 episodes) |
| Tier 4 | ⏳ Planned | Remaining transcripts (~130 episodes) |

**Estimated Total**: 800-1,200 SOPs when complete

### Contributing

Contributions welcome! See our extraction methodology in `/docs/sop-to-skills-plan.md`.

### License

This project extracts and organizes publicly available podcast content for educational purposes. All frameworks are attributed to their original sources.

---

<a name="中文"></a>
## 中文

### 项目概述

这是一个从 [Lenny's Podcast](https://www.lennyspodcast.com/)（产品管理和增长领域排名第一的播客）中提取的**标准操作程序（SOP）**合集。这些 SOP 将专家洞见转化为可立即应用的实用框架。

> **当前状态**：最重要的Tier 1 & 2 已完成（约50个播客，52 个 SOP / 9 个 Claude 技能）
> Tier 3 & 4 进行中（约 280 个播客待处理，预计 750-1,150 个 SOP）

### 包含内容

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
| `/sop-library` | 浏览全部 52 个 SOP | 按领域、场景、来源索引 |

#### 52 个 SOP（按领域分类）

| 领域 | 数量 | 核心框架 |
|------|------|----------|
| 领导力 | 9 | 彻底坦诚、创始人模式、公司操作系统 |
| 增长 | 8+ | 相邻用户理论、PLG、Kindle Fire |
| PM 技能 | 7 | PM 能力模型、产品感觉、高主动性 |
| 产品战略 | 5 | 战略栈、DHM、七种力量 |
| 上市策略 | 5 | JTBD、定位、支付意愿 |
| 优先级与目标 | 5 | NCT、GEM、LNO、事前验尸 |
| 决策 | 3 | SPADE、名义小组法、终止标准 |
| 发现 | 2 | 赋能团队、机会解决方案树 |
| 招聘 | 2 | 首位 PM、招聘领导者 |
| 沟通 | 2 | 高管沟通、隐喻对齐 |
| 其他 | 4 | A/B 测试、独立意见 |

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
| Tier 3 | 🔄 进行中 | 标准播客（约 150 期） |
| Tier 4 | ⏳ 计划中 | 剩余播客（约 130 期） |

**预计总计**：完成后 800-1,200 个 SOP

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
