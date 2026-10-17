# marketing-campaign-planner-skill

先看 [Fieldnote 活动简报示例 / fictional campaign brief](examples/fictional-campaign.md)：渠道取舍、任务排期、素材和衡量边界。[交付模板 / template](templates/campaign-brief.md) · [Skill 入口](SKILL.md)。

## 中文
这是个人自用、持续更新中的营销工作流项目。首版聚焦可直接交给 AI agent 的轻量工作方法，不代表已经获得业务效果，也不是自动发布或投放工具。

用途：营销活动策划、执行简报、素材任务及复盘设计。先复用已有且允许读取的业务资料，标明来源，再补充关键缺口。支持品牌账号、创始人/员工账号、合作方/客户账号的角色区分；不虚构背书。

使用：把整个目录复制到你的 agent 支持的 skill 目录（请按所用产品的说明安装），或让 agent 阅读 SKILL.md。提供业务目标、受众、资源、已有素材和事实依据，要求输出 templates/ 中的简报。examples/ 为明确标注的虚构示例，不能当作真实案例。无需 API key、付费测试或安装脚本。

示例请求：“为我提供的工作坊意向登记活动做两周执行简报。一个人每周三小时、预算为零；比较可行渠道，列任务负责人、素材要求、衡量口径和发布前缺口，不执行活动。”

交付：使用 [campaign brief](templates/campaign-brief.md) 整理目标与受众、渠道取舍、容量内排期、一份代表素材、衡量定义和待确认事项。目标是计划，不是已发生的报名或转化。

## English
Personal-use marketing workflow, continuously updated as real use reveals improvements. This is a first usable version, not a claim of proven business performance.

Scope: Campaign planning, execution briefs, and review gates. Read SKILL.md with an AI agent, supply a brief and permitted source material, and use the output template. Copy the full folder only when your agent supports local skills; follow that agent's installation instructions. No runtime dependencies, credentials, paid tests, or automatic publishing are required.

Example: “Plan a two-week workshop-interest campaign for one organizer with three hours/week and no budget. Compare feasible channels, assign asset tasks and define measurement and readiness checks; do not launch.” Return the campaign brief, a representative draft asset and unresolved approval/evidence gaps.

Files: SKILL.md is the workflow; references/ contains the adapted method; templates/ contains the output structure; examples/ contains fictional practice material. THIRD_PARTY_NOTICES.md and licenses/ preserve upstream attribution and terms.

## Sources and license scope / 来源与许可
One narrowly adapted module from coreyhaines31/marketingskills: skills/launch/SKILL.md, pinned at 365b412152b9542499ca1439426f7fc3cc92bb65. Actual upstream MIT LICENSE checked on 2026-10-16. See THIRD_PARTY_NOTICES.md for exact links and modifications. No repository-wide license is assigned to original additions by this package; the preserved MIT license applies to its identified upstream material.

Current targeted checks: [2026-10-17 targeted rule repairs and independent first-answer evidence](cases/round3-repair-2026-10-17/README.md). Initial partial results and later checks are reported separately. / 本轮规则修复、独立首稿及审核记录。
