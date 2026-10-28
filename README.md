# Top 20 Agent Skills 必装榜

> 面向 Claude Code / Cursor / Codex 等 AI 编程助手的 SKILL.md 技能包精选合集。
> 整理时间：2026-10-29

## 榜单列表

| 排名 | Skill | 仓库地址 | 简介 |
|:---:|---|---|---|
| 01 | **superpowers** | https://github.com/obra/superpowers | 全流程开发技能集（头脑风暴→TDD→调试→代码评审），约30万星 |
| 02 | **skills** | https://github.com/anthropics/skills | Anthropic 官方技能集（frontend-design、pptx、docx、xlsx、pdf、webapp-testing 等） |
| 03 | **andrej-karpathy-skills** | https://github.com/multica-ai/andrej-karpathy-skills | Karpathy 编码行为准则（先思考再写码、简洁优先、外科手术式改动、目标驱动） |
| 04 | **skills** | https://github.com/mattpocock/skills | Matt Pocock 的工程技能集（grill-me、tdd、implement、code-review、改善架构等） |
| 05 | **ponytail** | https://github.com/dietrichgebert/ponytail | 阻止 AI 写多余代码和过度工程化，保持项目简洁 |
| 06 | **ui-ux-pro-max-skill** | https://github.com/nextlevelbuilder/ui-ux-pro-max-skill | UI/UX 设计智能（风格、配色、字体、组件、无障碍） |
| 07 | **graphify** | https://github.com/Graphify-Labs/graphify | 将代码库、文档、SQL schema、PDF 转成知识图谱 |
| 08 | **caveman** | https://github.com/JuliusBrussee/caveman | "穴居人式"极简输出，压缩约65%冗余 token |
| 09 | **agent-skills** | https://github.com/VoltAgent/awesome-agent-skills | 1000+ 官方与社区 Agent Skills curated 合集 |
| 10 | **taste-skill** | https://github.com/Leonxlnx/taste-skill | 前端设计品味（brandkit、image-to-code、视觉调校） |
| 11 | **Understand-Anything** | https://github.com/Egonex-AI/Understand-Anything | 代码库分析与交互式知识图谱（架构/组件/依赖关系） |
| 12 | **impeccable** | https://github.com/pbakaus/impeccable | 检测并修复 27 种 UI 反模式（过用字体、配色失衡、动效滥用等） |
| 13 | **awesome-claude-skills** | https://github.com/ComposioHQ/awesome-claude-skills | 1000+ Claude Skills 的 awesome 大列表 |
| 14 | **last30days-skill** | https://github.com/mvanhorn/last30days-skill | 跨 Reddit/X/YouTube/HN/GitHub/TikTok 等做近30天实时舆情与趋势调研 |
| 15 | **humanizer** | https://github.com/blader/humanizer | 去除 AI 腔调与套话，让文本读起来像真人写的 |
| 16 | **diagram-design** | https://github.com/cathrynlavery/diagram-design | 生成 13+ 种编辑级图表（架构图、流程图、时序图、ER图、泳道图等）为 HTML/SVG |
| 17 | **i-have-adhd** | https://github.com/ayghri/i-have-adhd | ADHD 友好输出——结论先行、行动优先、不埋没答案 |
| 18 | **marketingskills** | https://github.com/coreyhaines31/marketingskills | 营销技能集（SEO 审计、文案、CRO、AB测试、数据分析等40+技能） |
| 19 | **academic-research-skills** | https://github.com/Imbad0202/academic-research-skills | 学术研究全流程（选题→综述→写作→多轮审稿→引用规范） |
| 20 | **scientific-agent-skills** | https://github.com/K-Dense-AI/scientific-agent-skills | 科学计算技能包（科研工作流、数据库、专用工具） |

## 安装方式

大多数 Skill 支持以下方式安装到 Claude Code：

```bash
# 通过 npx skills CLI 安装单个 skill
npx skills add <仓库地址> --skill <skill名称>

# 或通过 Claude Code 插件市场
/plugin marketplace add <仓库地址>
/plugin install <skill名>@<marketplace名>
```

## 备注

- #2 和 #4 都叫 "skills"：#2 是 Anthropic 官方的 `anthropics/skills`，#4 是 Matt Pocock 的 `mattpocock/skills`。
- #7 graphify 另有一个同名变体在 `akillness/oh-my-skills` 仓库下。
- #11 Understand-Anything 上游也有镜像 `Lum1104/Understand-Anything`。
