# 🔬 AI B2B Product Deep Research Skill

> Turn any AI assistant into a professional product growth researcher.  
> 让任何 AI 助手变成专业的产品增长研究员。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## What is this?

A **reusable AI skill** (prompt engineering framework) that helps AI startup founders systematically study how successful AI B2B products grew — especially their **early-stage decisions**, **seed user acquisition**, and **path to PMF**.

这是一套 **可复用的 AI 技能**（提示词工程框架），帮助 AI 初创团队系统化学习成功 AI B2B 产品的增长经验——特别是**早期决策**、**种子用户获取**和**找到 PMF 的过程**。

## Why?

Most case studies only tell you *what happened*. This skill digs into *why it happened* — the founder's psychology, the counter-intuitive decisions, the specific story of the first paying customer, and the 5-8 inflection points that changed everything.

大多数案例研究只告诉你"发生了什么"。这个 Skill 深挖"为什么会这样"——创始人心理、反直觉决策、第一个付费客户的故事、以及改变一切的关键拐点。

## Quick Start

### Option 1: Use with Cursor IDE (Recommended)

1. Clone this repo into your project
2. The `.cursorrules` file will be automatically picked up by Cursor
3. Ask: *"帮我深度调研 Cursor 这个产品"* or *"Research Perplexity for me"*
4. AI will follow the full 7-dimension, 37-question methodology automatically

### Option 2: Use with Any AI (ChatGPT, Claude, Gemini, etc.)

1. Open [`prompt.md`](prompt.md)
2. Copy the prompt template (Chinese or English version)
3. Replace `[PRODUCT_NAME]` with the product you want to research
4. Paste into your AI tool of choice

### Option 3: Manual Research Guide

1. Open [`docs/methodology.html`](docs/methodology.html) in a browser
2. Follow the 7 dimensions, 37-question checklist, and 4-day research process
3. Use the 11-chapter report template to structure your output

## Project Structure

```
ai-b2b-research-skill/
├── .cursorrules          # Core AI skill file (works with Cursor IDE)
├── prompt.md             # Universal prompt template (for ChatGPT/Claude/etc.)
├── README.md             # You are here
├── LICENSE               # MIT License
├── docs/
│   └── methodology.html  # Visual methodology guide (open in browser)
└── examples/
    └── Clay_深度研究报告.html  # Example report: Clay ($0 → $3.1B)
```

## The 8 Research Dimensions

| # | Dimension | Key Question |
|---|-----------|-------------|
| 1 | 🧠 **Founder Psychology** | WHY did they make this decision? |
| 2 | 🎯 **ICP Progression** | How did the target customer evolve? |
| 3 | 🌱 **Seed User Acquisition** | Where did the FIRST users come from? |
| 4 | 🔄 **PMF Discovery** | How many pivots to find PMF? |
| 5 | 💰 **Pricing Design** | How does pricing drive growth? |
| 6 | 📣 **Growth Flywheel** | Brand × Content × Community? |
| 7 | ⚔️ **Competitive Differentiation** | WHY do customers choose THIS over competitors? |
| 8 | ⚡ **Inflection Points** | What events changed the growth curve? |

## The 4-Layer Seed User Funnel

```
Layer 1: Community Infiltration
  └─ Join target communities, provide value (not pitch)
  └─ Build trust over months as "the expert"

Layer 2: Power Node Activation  
  └─ Find the community's most connected person
  └─ Recruit them as co-founder/advisor (not just KOL)

Layer 3: High-Touch Conversion
  └─ Reverse demos: customer brings the problem, you solve it live
  └─ 8+ demos/day, evolving from 7-touch to 0-touch conversion

Layer 4: Community Lock-in
  └─ All support via community (Slack/Discord), not 1:1
  └─ Community = support + feedback + content + moat
```

## The 5-Layer Competitive Moat Model

```
Layer 1: Landscape Mapping
  └─ Who are the competitors? What was the "old way" before this product?

Layer 2: Counter-Positioning
  └─ What does this product deliberately NOT do that competitors do?
  └─ What "industry standard" did they reject? Why is that an advantage?

Layer 3: "Why Switch" Story
  └─ For customers who left a competitor — what was the #1 trigger?
  └─ What "aha moment" can't competitors replicate?

Layer 4: Competitive Response Playbook
  └─ When a competitor copies a key feature — ignore / differentiate / pivot?
  └─ Internal decision-making process for competitive threats

Layer 5: Moat Construction
  └─ Network Effects (community, ecosystem, integrations)
  └─ Switching Costs (data lock-in, workflow dependency)
  └─ Brand (trust, reputation, emotional connection)
  └─ Scale Economies (data advantage, cost structure)
  └─ Counter-Positioning (incumbents CAN'T copy without self-harm)
```

## Example Report

📄 **[Clay: From $0 to $3.1B](examples/Clay_深度研究报告.html)** — A company that spent 7 years finding PMF, then grew 10x → 6x → to a $3.1B valuation.

Open the HTML file in your browser to see the full interactive report.

## Report Quality Scoring

Every report is evaluated on 7 criteria (100 points total):

| Criteria | Points | What it measures |
|----------|--------|-----------------|
| Founder Insight Depth | 20 | Understanding the psychology behind decisions |
| Seed User Story | 15 | Clear reconstruction of first user acquisition |
| PMF Process | 15 | Understanding why growth suddenly exploded |
| Data Accuracy | 15 | All data traceable to primary sources |
| Actionability | 15 | Other founders can directly reuse insights |
| Visualization | 10 | Clear, beautiful, persuasive charts |
| Story Quality | 10 | Reads like a startup documentary |

**70+ = Pass · 80+ = Good · 90+ = Benchmark**

## Suggested Products to Research

- **Cursor** — AI Code Editor
- **Perplexity** — AI Search Engine
- **v0** — AI UI Generation (Vercel)
- **Eleven Labs** — AI Voice
- **Midjourney** — AI Image Generation
- **Runway** — AI Video
- **Notion AI** — AI Workspace
- **Jasper** — AI Content

## Contributing

Found a way to improve the methodology? PRs welcome!

- Add new research dimensions
- Improve the prompt templates
- Submit example reports for other products
- Translate to other languages

## License

MIT — Use it, fork it, improve it, share it.

---

*Built by AI startup founders, for AI startup founders.*  
*由 AI 创业者打造，为 AI 创业者服务。*
