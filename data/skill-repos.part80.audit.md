# part80：教育、科研计算与文献管理来源扩展

核验日期：2026-10-15（Asia/Shanghai）。基线 2116 个仓库，核验 26 个独立新候选，新增 16 个，暂缓或排除 10 个；目录合计 **2132**。另修正 1 条既有来源的重叠标注。技能正文仍为 1113 条，没有导入第三方指令。

## 基线与方法

- 实际项目为 E:\Everthing-Skills；在已有 part79 的干净 zh 工作区继续。本地 main/zh 含 2116 条，已覆盖远端 main/zh 的 2106 条，不把尚未推送的 10 条重收。本轮不合并、不推送、不清理分支或改每日任务。
- 使用 agent-reach 的 GitHub/API 路线及 research-ops 的证据边界。Exa MCP 不可用，采用已有网页检索发现线索；browser-harness 检查无活动连接，核验直接读取公开 API 与固定提交文件，不要求重新设置浏览器。
- 保留仓库 ID、Stars 当日快照、规范名称、commit SHA 与 tree SHA；阅读全文入口、许可证和代表性技能，保存原始字节 SHA256。所有新增代表入口有 name/description；计算化学候选额外检查了全部 67 条公开技能的 frontmatter。
- 只更新索引元数据，不安装、不执行、不 clone 候选，不声称其教学、科学计算或跨 Agent 效果已实测。

完整证据见 [机器审核](skill-repos.part80.audit.json)、[检索来源](skill-repos.part80.search-provenance.json)与[后续检索范围](skill-repos.discovery-scope.json)。

## 新增仓库

| 仓库 | 类型 | Stars | 核验计数 | 摘要 |
|---|---|---:|---|---|
| [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf) | 产品、SDK、CLI 内嵌技能 | 29707 | 1 | OpenDataLoader PDF 产品附公开 Agent Skill，用于结构化提取、格式选择与运行时 CLI 发现；企业版 PDF/UA 服务另计。 |
| [scayver/marketing-skills](https://github.com/scayver/marketing-skills) | 行业创作与迁移单仓库 | 8 | 76 | Marketing Skills OS 公开技能库，覆盖策略、内容、SEO、营销活动、无障碍设计、评分卡与执行工作流。 |
| [dtunai/agent-skills-for-compute](https://github.com/dtunai/agent-skills-for-compute) | 科学计算、计算化学与 HPC 工作流 | 2 | 21 | 计算技能包，覆盖 GPU/TPU/QPU 编程、科学仿真、Slurm/MPI、量子工具及模型训练推理。 |
| [BTHawake/Teacher_skill](https://github.com/BTHawake/Teacher_skill) | 教学、课程设计与学习诊断 | 2 | 1 | 中文教师技能，包含教学路由、引导提问、学习诊断与按任务读取的参考材料。 |
| [tizzy916/scholar-wendao-skill](https://github.com/tizzy916/scholar-wendao-skill) | 数字人文、策展、档案与设计史 | 20 | 1 | 学者视角提问与对话技能，内容许可带非商业限制；仅索引仓库元数据，不采编其指令正文。 |
| [Axect/skills](https://github.com/Axect/skills) | 实验室与可复现科研工作流 | 3 | 30 | 面向研究者的技能集合，覆盖文献、论文审查、学术机会、科研图表、写作与研究运营。 |
| [learning-commons-org/agent-skills](https://github.com/learning-commons-org/agent-skills) | 教学、课程设计与学习诊断 | 38 | 4 | Learning Commons 教学技能，覆盖理解检查、差异化教学、教案创建与备课，附可选教育 MCP 集成。 |
| [mprokopov/teaching-skills](https://github.com/mprokopov/teaching-skills) | 教学、课程设计与学习诊断 | 0 | 2 | 课程设计技能：根据教学大纲映射前置能力图谱并构建入学准备度诊断。 |
| [polgarp/collage-design](https://github.com/polgarp/collage-design) | 数字人文、策展、档案与设计史 | 2 | 1 | 拼贴设计技能，利用档案照片与印刷材料，记录来源和署名，并组织 SVG/PNG 图像合成。 |
| [nraford7/art-direct](https://github.com/nraford7/art-direct) | 行业创作与迁移单仓库 | 9 | 1 | 艺术指导技能，将文档等内容整理为视觉方向、图像提示词与制作简报。 |
| [SciMate-AI/HPC-Skills](https://github.com/SciMate-AI/HPC-Skills) | 科学计算、计算化学与 HPC 工作流 | 95 | 22 | 可移植 HPC 技能，覆盖 CFD、FEM、分子模拟、量子化学、MPI、GPU、Spack、可视化及集群编排。 |
| [yale-som-hpc/claude-code-marketplace](https://github.com/yale-som-hpc/claude-code-marketplace) | 科学计算、计算化学与 HPC 工作流 | 5 | 23 | Yale SOM 研究计算技能市场，覆盖特定集群的 HPC、Python/R/Stata、Slurm、存储、GPU 与可复现流程。 |
| [Genentech/openfe_skill](https://github.com/Genentech/openfe_skill) | 科学计算、计算化学与 HPC 工作流 | 28 | 1 | Genentech OpenFE 技能，用于 Slurm HPC 上的相对结合自由能工作流，站点配置单独保存。 |
| [WenyuChiou/zotero-skills](https://github.com/WenyuChiou/zotero-skills) | 文献管理、本地文献库与引文工作流 | 58 | 1 | Zotero 文献库操作与科研工作流技能，通过作者维护的研究技能市场公开分发。 |
| [AkaLiu/zotero-skill](https://github.com/AkaLiu/zotero-skill) | 文献管理、本地文献库与引文工作流 | 5 | 1 | 双语本地 Zotero 文献技能，用于论文和笔记检索、PDF 阅读及有文献上下文的研究辅助。 |
| [jinzhezenggroup/computational-chemistry-agent-skills](https://github.com/jinzhezenggroup/computational-chemistry-agent-skills) | 科学计算、计算化学与 HPC 工作流 | 151 | 67 public files (incl. routers) | 计算化学工作流，覆盖量子化学、原子仿真、分子动力学、数据准备、声子与机器学习势；各技能保留自己的许可声明。 |

## 计数与许可边界

- OpenDataLoader：只计公开 odl-pdf 技能，排除内部 odl-fix；根 README 介绍产品，另外读取 skills/README.md 与技能自己的 README 验证公开安装入口，避免只看产品 Stars。
- Compute：21 条公开技能，排除 1 条内部 validate-skills；Yale SOM 的 23 条技能包含集群专属设置，不宣称所有环境可直接运行。
- 计算化学：67 个公开技能文件含层级路由，另有 1 个内部维护入口。67 条都有 name/description，36 条声明 LGPL-3.0-or-later、24 条 MIT、7 条未单独声明；根许可证为 LGPL-3.0。保留分层许可信息，不用根标签覆盖所有文件。
- Scholar-Wendao：只计根入口，排除 2 个示例；许可是 CC-BY-NC-4.0，属于带非商业限制的内容，只收元数据，禁止把本次索引视为采编或商业复用授权。
- Learning Commons：4 条技能中 1 个 blob 与已有 Anthropic K-12 源相同，另外 3 个不同；保留独立发布源，并注明重叠，不将其计为 4 个全局新能力。
- Axect 的 30 条为当前入口，已改名为 SKILL.md.deprecated 的历史条目不计；Teacher_skill 的科目资料不是多个独立技能。
- 本轮有 1 次代表文件 TLS 读取失败，重试成功后采用固定提交的实际字节哈希，没有以失败样本或空哈希准入。

## 既有重叠来源复核

- 对已索引的 datadrivenconstruction 与 part79 新增 zstary 两个 DDC 仓库，读取各自固定提交树。前者 238 个技能文件，后者 221 个，其中 **192 个 blob 字节相同、29 个不匹配**。这证明大量重叠，不能证明整库完全相同；保留仓库索引，并将 part79 计数和摘要改成明确重叠的表述。
- 本轮不推定作者身份、复制动机或差异文件的实际收益，不将未匹配文件自动视为原创能力。

## 暂缓或排除

| 仓库 | 原因 |
|---|---|
| [TianyuDu/SLURM-HPC-AGENT-SKILL](https://github.com/TianyuDu/SLURM-HPC-AGENT-SKILL) | 两个大小写/URL 线索归一为同一仓库 ID；有 2 条技能，但没有许可证文件或许可元数据。 |
| [roohe/agentic-super-skills](https://github.com/roohe/agentic-super-skills) | 固定树有 2600 个技能文件，README 的 6000+ 不作为计数依据；没有许可证，暂缓。 |
| [ImperialCollegeLondon/ese-borg-skills](https://github.com/ImperialCollegeLondon/ese-borg-skills) | 7 个技能文件及公开市场入口存在，但未发现许可证；机构名称不代替许可证据。 |
| [settylab/fh-hpc-skills](https://github.com/settylab/fh-hpc-skills) | 39 个集群技能文件有公开安装说明，未发现许可证，暂缓。 |
| [JayClock/.agents](https://github.com/JayClock/.agents) | 10 个个人技能入口存在，但没有许可证，暂缓。 |
| [ketthub/zotero-skill](https://github.com/ketthub/zotero-skill) | 本地 Zotero 检索技能有安装说明，但没有许可证，暂缓。 |
| [c0mm4nd/zotero-skills](https://github.com/c0mm4nd/zotero-skills) | 2 条 Zotero 技能和插件入口存在，但没有许可证，暂缓。 |
| [Bubble-OoO/zotero-research-assistant-skill](https://github.com/Bubble-OoO/zotero-research-assistant-skill) | 有根 SKILL.md，但没有许可证，暂缓。 |
| [dougwyu/claude-zotero-skills](https://github.com/dougwyu/claude-zotero-skills) | 许可证原文为 Apache-2.0，但仓库分发旧式命名的单文件提示词，树中没有标准 SKILL.md 或相应技能包；不为此轮临时放宽格式准入。 |
| [SFETNI/Deep-Matter-Chem-Skills](https://github.com/SFETNI/Deep-Matter-Chem-Skills) | 固定树 60 个技能文件与 README 65 徽标不一致；跨三个领域抽查的 frontmatter 均没有 description，尚未满足标准发现字段要求。 |

## 本地验证

- `node scripts/build-all.mjs --lang=zh` 全量生成通过；共享 JSONL 加载器校验通过，共 2132 个大小写去重后的独立仓库。
- 16 条新增记录的仓库 ID、Stars、许可、计数和证据路径与审核记录一致；合格/排除合计 26 条，所有新增代表技能都有 name/description。
- README 与 INDEX 包含全部 16 条新增链接；技能正文仍为 1113 条，关系边仍为 6800 条。
- 与研究开始前的逐文件 SHA256 对比，既有变动仅限预期的索引、品牌统计、scope/meta 与 part79 重叠标注；没有修改技能正文、生成器或测试，也没有改变已有提交。`git diff --check` 通过。
- 本轮提交到当前本地 zh，随后执行 `node scripts/check-generated.mjs --lang=zh`。不推送、不合并、不删除分支，不修改每日任务。
