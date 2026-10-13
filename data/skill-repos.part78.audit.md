# part78：公益政务、能源工业与产品内嵌技能扩展

核验日期：2026-10-13（Asia/Shanghai）。基线 2090 个仓库，检查 26 个新候选；新增 16 个，暂缓或排除 10 个，合入后 **2106**。仅增加仓库索引，技能正文仍为 1112 条。

## 接续与核验方法

- 已接续 part76、part77 和合并后的 main/zh。最近两次旧聊天运行记录因用量限额失败，本轮在当前聊天继续；每日任务的计划及权限未修改。
- 当前 zh 工作区干净，已 fetch origin；本地与远端 main/zh 的 data 文件一致。按名称、规范名称及已知仓库 ID 去重，采用未占用的 part78。
- 沿用 agent-reach 的 GitHub/检索路线，并使用 browser-harness 查看公开仓库。以 GitHub REST 元数据、固定 commit/tree、原始 README、许可和代表性 SKILL.md 为准，搜索引擎只提供线索。
- 全部合格项代表技能的 name、description 非空；存储日期、Stars、仓库 ID、commit/tree SHA、原始文件 SHA256 和来源链接。不安装、执行或克隆任何候选，不导入技能正文。
- 未逐条执行或评测候选，也未验证其科学、法律、监管、临床或营销效果。许可证标签不授权后续采编；后续复制仍需逐文件复核。

完整证据见 [机器审核](skill-repos.part78.audit.json)、[检索来源](skill-repos.part78.search-provenance.json)及[扩展检索范围](skill-repos.discovery-scope.json)。

## 合格新增

| 仓库 | 类型 | Stars 快照 | 技能计数 | 摘要 |
|---|---|---:|---|---|
| [manojsurapaneni/manufacturing-ops-skills](https://github.com/manojsurapaneni/manufacturing-ops-skills) | 电网、能源公用事业与工厂运营 | 2 | 1 | 工厂运营技能：Toyota 风格 A3 问题报告、根因调查与持续改进初稿。 |
| [TuringWorks/civstack](https://github.com/TuringWorks/civstack) | 公益筹款、政务与城市数据、规划及公共采购 | 1 | 433 core (+30 views) | CivStack 公共经济角色与工作流库，涵盖政务、公用事业、工业、环境及人员责任边界。 |
| [GeoGeekLab/nature-reviewer-skills](https://github.com/GeoGeekLab/nature-reviewer-skills) | 实验室与可复现科研工作流 | 48 | 8 | 独立的 Nature 风格稿件审查技能，覆盖化学、工程、材料与地球系统研究，附共享审查工具。 |
| [iamursky/carbon-skill](https://github.com/iamursky/carbon-skill) | 产品、SDK、CLI 内嵌技能 | 5 | 1 | IBM Carbon UI 技能，覆盖 React、Web Components、Sass、主题、网格与图标；随附参考文档使用独立许可。 |
| [SkillMedev/nonprofit-grants-toolkit](https://github.com/SkillMedev/nonprofit-grants-toolkit) | 公益筹款、政务与城市数据、规划及公共采购 | 0 | 6 | 小型公益组织技能：资助方研究、意向函、申请书、捐赠者沟通、影响报告与理事会准备。 |
| [sgarcese/Civic-Analytics-Agent-Workflow-Claude-Skill](https://github.com/sgarcese/Civic-Analytics-Agent-Workflow-Claude-Skill) | 公益筹款、政务与城市数据、规划及公共采购 | 40 | 1 | 城市公共政策分析工作流技能，串联问题界定、开放城市数据、分析与证据报告。 |
| [scottconverse/civic-scanner](https://github.com/scottconverse/civic-scanner) | 公益筹款、政务与城市数据、规划及公共采购 | 0 | 1 | 便携城市新闻编辑室技能，用于地方报道、主张核验与带来源的编辑初稿，附跨代理安装器。 |
| [Amazon-Quick/Amazon-Quick-official-catalog](https://github.com/Amazon-Quick/Amazon-Quick-official-catalog) | 产品、SDK、CLI 内嵌技能 | 50 | 102 | Amazon Quick 桌面技能目录，覆盖业务工作流，含 14 条能源公用事业技能及供应链任务。 |
| [terravic/bid-protest-architect-skill](https://github.com/terravic/bid-protest-architect-skill) | 公益筹款、政务与城市数据、规划及公共采购 | 0 | 1 | 面向 Agent 的美国联邦采购文件审计与采购异议起草技能；未独立验证其法律与申报有效性。 |
| [Hugin-Z/tender-writer-v4](https://github.com/Hugin-Z/tender-writer-v4) | 公益筹款、政务与城市数据、规划及公共采购 | 12 | 1 | 以 Windows 为主要环境的政府项目投标应答技能，覆盖文件解析、评分矩阵、结构化初稿、附件组装与导出。 |
| [BrightCubes/power-grid-model-ai](https://github.com/BrightCubes/power-grid-model-ai) | 电网、能源公用事业与工厂运营 | 3 | 2 | Power Grid Model 生态技能，覆盖数据导入、校验、电网计算、结果解释与问题分析。 |
| [Nolpak14/getregdata](https://github.com/Nolpak14/getregdata) | 公益筹款、政务与城市数据、规划及公共采购 | 6 | 44 | 企业登记数据研究技能，用于企业核验、尽调、公开申报及跨境研究；部分流程依赖外部付费 Actor。 |
| [wentorai/research-plugins](https://github.com/wentorai/research-plugins) | 实验室与可复现科研工作流 | 298 | 433 tasks + 40 routers | 科研龙虾学术工作流库，含 433 条任务技能、40 条路由入口及单独计数的数据库工具集成。 |
| [SeagullTwo/uk-planning-skills](https://github.com/SeagullTwo/uk-planning-skills) | 公益筹款、政务与城市数据、规划及公共采购 | 1 | 15 | 英国规划文件技能，涵盖申请分诊、生态、交通、遗产、洪水、政策评估、报告与委员会准备。 |
| [dungnotnull/historical-cadastral-map-restoration-agent-skill](https://github.com/dungnotnull/historical-cadastral-map-restoration-agent-skill) | 数字人文、策展、档案与设计史 | 5 | 1 | 历史地籍图修复与 GIS 数字化 Agent 工作流，附研究及参考材料。 |
| [benjaminjackson/nonprofit-fundraising-skills](https://github.com/benjaminjackson/nonprofit-fundraising-skills) | 公益筹款、政务与城市数据、规划及公共采购 | 1 | 2 | 公益组织捐赠者维护与捐赠者通讯 Claude 插件技能，采用按任务路由的参考库。 |

## 计数和版本边界

- CivStack：skills/ 有 433 个核心包，另有 30 个 agentic-workforce 视图；不把 463 文件宣称为 463 个独立核心技能。核心目录本身包含路由及角色目录。
- 科研龙虾：473 个 SKILL.md = 433 条叶子任务技能 + 40 条父级路由；34 个数据库 API 工具单独计算。templates 目录里的真实模板写作技能不因目录名而误删。
- Civic Scanner：当前根入口 1 条，排除 12 个历史版本副本。英国规划：15 个当前根目录，排除 9 个 nppf-2024-12 历史副本。
- 电网模型：公开 PGM 助手与问题分析 2 条，排除技能自身更新维护入口 1 条；README 的旧 pgm-issues 链接与当前 pgm-issue-analysis 路径不同，已依据真实树记录。
- 投标写作：v2 的 README 指向活跃 v4；仅新增 v4。工厂运营：只计已交付的 A3 技能，不计 roadmap 计划。城市分析：5 个流程阶段不等于 5 个 SKILL.md。
- Carbon 是设计系统名称，不能计为碳排放技能：技能 MIT，随附 Carbon 参考文档 Apache-2.0；另两个 Carbon 产品仓库的贡献者技能未入库。
- Amazon Quick：固定提交含 102 条技能，其中 14 条 energy-utilities；许可为 MIT-0，未误写成 MIT。
- 新增能源工业与公益运营两个检索 family，后续轮换公益、城市开放数据、公共采购、电网、公用事业和工厂管理，继续沿 SDK/产品原生目录与活跃后继追踪。

## 暂缓或排除

| 候选 | 原因 |
|---|---|
| [getburo/buro-free](https://github.com/getburo/buro-free) | README 提供技能市场，但 LICENSE 明确 All Rights Reserved；free tier 不等于开源授权，暂缓。 |
| [lyndonkl/claude](https://github.com/lyndonkl/claude) | 271 个 SKILL.md 文件，但仓库树和元数据没有许可证，暂缓。 |
| [oldwinter/skills](https://github.com/oldwinter/skills) | 10 个技能文件，只有 tdd-pstack 与 teach-pstack 子目录有许可证；其余条目授权范围未明确，不以局部授权覆盖整库。 |
| [HinVec/awesome-skills_lists](https://github.com/HinVec/awesome-skills_lists) | GitHub 标记为 fork，未读其正文；不重复收录 fork 分发。 |
| [crbnos/carbon](https://github.com/crbnos/carbon) | 制造 ERP 产品含 36 个 .claude/ 贡献者技能；根 README 未证明它们作为公开技能包分发，且整体许可分区需继续厘清。 |
| [carbon-design-system/carbon-ai-chat](https://github.com/carbon-design-system/carbon-ai-chat) | 21 个技能文件是 7 个贡献者流程的三个客户端副本，根 README 介绍组件 SDK，未提供独立技能分发证据。 |
| [infometa/workbuddyskills](https://github.com/infometa/workbuddyskills) | 2929 个技能文件混有众多连接器与第三方来源；没有统一根许可，仅部分子包提供许可证，暂缓逐源核验。 |
| [HumboldtJoker/coalition-agent-skills](https://github.com/HumboldtJoker/coalition-agent-skills) | 4 个 SKILL.md 文件，没有许可证文件或许可元数据，暂缓。 |
| [Hugin-Z/tender-writer-v2](https://github.com/Hugin-Z/tender-writer-v2) | README 明确停止维护并指向 v4；仅新增已核验的活跃后继，不重复新增旧入口。 |
| [plurigrid/asi](https://github.com/plurigrid/asi) | 3172 个 SKILL.md 混有嵌套项目；确认 skills/bmorphism__cc-trace/LICENSE.txt 为 MS-RSL，不能将根 MIT 推定到全库；首次代表文件也缺标准 frontmatter，暂缓来源及入口核验。 |

## 本地验证

- `node scripts/build-all.mjs --lang=zh` 全量生成通过：1112 条技能、11 卷、6795 条关系边、2106 个仓库。
- 16 条新增 JSONL 与审核记录中的 ID、Stars、许可、计数、日期相符；合格/暂缓数量一致，来源链接固定至所核验 commit，commit SHA 与 tree SHA 分别记录。
- README 与 INDEX 包含全部 16 条新增链接；未修改任何技能正文、脚本或测试源文件。`git diff --check` 通过。
- 在当前 `zh` 本地分支提交本轮变更，提交后执行 `node scripts/check-generated.mjs --lang=zh`。不推送、不合并、不删除分支，不修改每日任务计划。
