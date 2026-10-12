# part77 审核记录

- 核验日期：2026-10-12 (Asia/Shanghai)
- 基线：2085 条；本轮合格新增：5 条；合入后：2090 条
- 范围：只更新仓库索引，不安装、执行、克隆候选，也不复制第三方技能正文。

## 合格新增

| 仓库 | Stars | 许可 | 技能计数 | 证据范围 | 代表入口 |
| --- | ---: | --- | ---: | --- | --- |
| [Community-Access/accessibility-agents](https://github.com/Community-Access/accessibility-agents) | 424 | MIT | 108 | 108 skills/*/SKILL.md entries at the fixed tree | [SKILL.md](https://github.com/Community-Access/accessibility-agents/blob/decf6bac7f086c19afb242797b4974671ceff597/skills/accessibility-lead/SKILL.md) |
| [mgifford/accessibility-skills](https://github.com/mgifford/accessibility-skills) | 51 | AGPL-3.0 | 33 | 33 canonical SKILL.md entries | [SKILL.md](https://github.com/mgifford/accessibility-skills/blob/ada839399f053c55e1a776a98c02f8904d70dd32/skills/ACCESSIBILITY-general/SKILL.md) |
| [pjt222/agent-almanac](https://github.com/pjt222/agent-almanac) | 37 | MIT | 373 canonical | README states 373 canonical skills across 67 domains | [SKILL.md](https://github.com/pjt222/agent-almanac/blob/6cf8915b43fa5745e600cecf8c996e5162a76eda/skills/translate-content/SKILL.md) |
| [PangenomeAI/academic-skills-food-nutrition](https://github.com/PangenomeAI/academic-skills-food-nutrition) | 35 | MIT | 41 | 41 distributed SKILL.md entries at the fixed tree | [SKILL.md](https://github.com/PangenomeAI/academic-skills-food-nutrition/blob/01b2158a48408a8d0e56238c04075080c793d53c/agri-deep-research/SKILL.md) |
| [codejunkie99/agentic-stack](https://github.com/codejunkie99/agentic-stack) | 2295 | Apache-2.0 | 16 | 16 .agent/skills/*/SKILL.md entries | [SKILL.md](https://github.com/codejunkie99/agentic-stack/blob/3848f275f5d227f355984d6c9ba67072202f94f9/.agent/skills/brain/SKILL.md) |

## 采编判定

- Local main and zh were compared case-insensitively by full_name before admission; no accepted candidate was already indexed.
- GitHub public metadata supplied repository IDs and Stars snapshots; fixed commit trees and raw files supplied README, license, representative SKILL.md, and hash evidence without running candidate code.
- Skill counts distinguish canonical public SKILL.md entries from translations, examples, archives, compatibility copies, agents, teams, guides, CLI files, and generated paths.
- PangenomeAI adds the agriculture/science family; accessibility candidates add a previously uncovered accessibility collection family.
- Forks, mirrors, no-license candidates, unresolved canonical URLs, documentation-only repositories, fixture-only repositories, and candidates with unresolved nested-license boundaries were excluded.

## 暂缓或排除

| 候选 | 原因 |
| --- | --- |
| `aipoch/medical-research-skills` | previously deferred in part75: nested/upstream license scope remains unresolved despite a root MIT file; keep separate until per-skill provenance is closed |
| `google/adk-docs` | documentation repository demonstrates a SkillToolset but does not expose a distributable skill collection or installable skill entry |
| `xueyang-dev/localize-anything` | GitHub canonical URL returned 404; installation source and current repository identity could not be verified |
| `lelouvincx/agent-skills` | README/SKILL evidence exists but repository license metadata and license file are absent |
| `hashgraph-online/skill-publish` | tree contains only test fixture SKILL.md files; no public distributable skill package |

## 核验说明

README、许可证、固定提交树与代表性 SKILL.md 均只读核验；`skill_count` 排除了翻译、示例、测试夹具、兼容副本、插件元数据及生成文件。候选仓库的安装入口只作为公开分发证据，不在本地安装或运行。

## 合并复核（2026-10-12）

- 候选总数修正为 10：合格新增 5 条，暂缓或排除 5 条，与两份列表一致。
- 按固定提交重新下载 5 个合格仓库的 README、许可证和代表性 SKILL.md；发现 pjt222/agent-almanac 的许可证 SHA-256 记录缺少最后一位 `a`，已按原始字节修正。许可证内容仍为 MIT。
