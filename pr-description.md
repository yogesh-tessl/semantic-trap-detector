Hey @Jumbo-WJB 👋

I ran your skills through `tessl skill review` at work and found some targeted improvements. Here's the full before/after:

| Skill | Before | After | Change |
|-------|--------|-------|--------|
| semantic-trap-detector | 72% | 88% | +16% |

![Score Card](score_card.png)

<details>
<summary>Changes made</summary>

**Description (82% → 100%)**
- Replaced generic actions ("detect and fix") with specific concrete actions: scan instructions, identify high-risk phrasing, rewrite problematic sections
- Narrowed overly broad trigger terms like "prompt engineering" and "optimizing prompts" to more specific scenarios: "debugging skill prompts that produce incorrect outputs", "auditing skill wording for semantic drift"
- Added explicit "Use when..." clause with four distinct trigger scenarios

**Content (48% → 70%)**
- Removed the 核心理论 (Core Theory) section — the ASCII sensitivity matrix and theoretical explanation consumed tokens without aiding task execution
- Removed FAQ section, version history, license/citation block — these don't help Claude execute the skill
- Removed 使用指南 (Usage Guide) section — natural language prompt examples aren't executable
- Removed 词典维护 (Dictionary Maintenance) section — maintenance docs belong in a contributor guide, not the skill body
- Condensed the 概述 (Overview) from two paragraphs to a focused summary with links to reference files
- Improved progressive disclosure by keeping the workflow compact and referencing semantic-trap-lexicon.md and test-cases.md for detail

All domain-specific content (the four-step workflow, keyword categories, risk classification, structural pattern detection, report format) is preserved.

</details>

Honest disclosure — I work at @tesslio where we build tooling around skills like these. Not a pitch - just saw room for improvement and wanted to contribute.

Want to self-improve your skills? Just point your agent (Claude Code, Codex, etc.) at [this Tessl guide](https://docs.tessl.io/evaluate/optimize-a-skill-using-best-practices) and ask it to optimize your skill. Ping me - [@yogesh-tessl](https://github.com/yogesh-tessl) - if you hit any snags.

Thanks in advance 🙏
