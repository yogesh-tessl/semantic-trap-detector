Hey @Jumbo-WJB 👋

I ran your skills through `tessl skill review` at work and found some targeted improvements. Here's the full before/after:

| Skill | Before | After | Change |
|-------|--------|-------|--------|
| semantic-trap-detector | 72% | 94% | +22% |

![Score Card](score_card.png)

<details>
<summary>What changed</summary>

**Description (82% → 100%)**
- Expanded with specific concrete actions (scan, identify, rewrite) instead of generic "detect and fix"
- Added targeted trigger terms ("debugging skill prompts", "semantic drift", "output leakage") to improve skill matching
- Narrowed overly broad terms like "prompt engineering" that could conflict with other skills

**Content (48% → 85%)**
- Condensed the 核心理论 section from ~30 lines to a brief summary with a link to the lexicon file — Claude doesn't need the full theory to execute the workflow
- Removed sections that don't aid task execution: FAQ, version history, license/citation block, dictionary maintenance instructions
- Trimmed the report template's verbose replacement example, referencing the lexicon's anchoring strategies instead of repeating them
- Removed the 使用指南 (invocation examples) — these describe how to call the skill, not how to execute it, so they belong in the description
- Improved progressive disclosure by referencing `semantic-trap-lexicon.md` and `test-cases.md` instead of duplicating their content

</details>

Honest disclosure — I work at @tesslio where we build tooling around skills like these. Not a pitch - just saw room for improvement and wanted to contribute.

Want to self-improve your skills? Just point your agent (Claude Code, Codex, etc.) at [this Tessl guide](https://docs.tessl.io/evaluate/optimize-a-skill-using-best-practices) and ask it to optimize your skill. Ping me - [@yogesh-tessl](https://github.com/yogesh-tessl) - if you hit any snags.

Thanks in advance 🙏
