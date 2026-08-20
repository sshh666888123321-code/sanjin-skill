# 阶段 1.5 三重验证通过池

> 判定规则：V1 必须有至少两个独立语境；V2 必须能回答候选原文未直接讨论的新问题；V3 必须具备作者的反直觉视角、独特结构或可复用术语。`merged_ids` 保留所有被合并的原候选 ID，原始引用仍以 candidates/*.md 为准。

## v01｜旧元素重组创新法

- `type`: framework
- `merged_ids`: f01, g01, g02, p007, c03, c04, c05, c45, c64
- `V1_cross_domain`: passed — 业务风口重组（f01/c03/c04）、AI 与既有知识资产重组（c05）、跨旅游与婚摄场景迁移（c45）；对象和业务语境不同。
- `V2_predictive_power`: passed — 新平台出现但没有新产品时，先列出现有客户、内容、交付和渠道能力，再与平台需求重组；可预测出应做“已有内容的低成本迁移测试”，而非追逐全新赛道。
- `V3_exclusivity`: passed — 将创新明确拆成“拆解—清空—重组”，并把风口解释为积累与新变化的相遇，不是追热点清单。
- `source_refs`: candidates/frameworks.md:f01；candidates/glossary.md:g01-g02；candidates/cases.md:c03-c05,c45,c64

## v02｜AI 放大已有资产判断框架

- `type`: framework
- `merged_ids`: f02, p008, p011, p029, c17, c56
- `V1_cross_domain`: passed — AI 调用搜索手册变培训（c05）、自用看板产品化（c17）、实操经验做陪跑产品（c56）。
- `V2_predictive_power`: passed — 面对一个新 AI 工具，先问已有客户问题、方法、案例能否被复制或标准化；若只能生成新奇内容、不能放大既有资产，则暂不投入。
- `V3_exclusivity`: passed — 反转“AI 能做什么新东西”为“AI 能把已有东西放大多少倍”，把变现支点放在存量资产。
- `source_refs`: candidates/frameworks.md:f02；candidates/principles.md:p008,p011,p029；candidates/cases.md:c05,c17,c56

## v03｜AI 知识库三层模型

- `type`: framework
- `merged_ids`: f03, g18, g19, g20, p010, p020, p052, c08, c09, c14
- `V1_cross_domain`: passed — 产品事实/案例/判断层（f03）、规则从错误日志迭代（c08）、内容配比监控（c09）和搜索 Skill（c14）分别验证了三层结构在知识、治理和生产场景的作用。
- `V2_predictive_power`: passed — 新项目接入 AI 时，若只有资料没有个人判断，输出应停留在信息层；应补“真实案例+取舍规则”后才允许让 AI 做推荐。
- `V3_exclusivity`: passed — 用信息层—故事层—判断层区分“资料库”和“能执行个人决策的知识库”。
- `source_refs`: candidates/frameworks.md:f03；candidates/glossary.md:g18-g20；candidates/principles.md:p010,p020,p052；candidates/cases.md:c08,c09,c14

## v04｜AI 原子任务—流程串联系统

- `type`: framework
- `merged_ids`: f04, f16, g07, p042, p054, p055, p073, c19, c27
- `V1_cross_domain`: passed — 小红书获客流程（f04）、账号内容生产（f16/c14）、数字人生产链路（c27）和 AI 设计、人工落地看板（c19）均采用单一职责拆分。
- `V2_predictive_power`: passed — 对一个“帮我做完整投放方案”的模糊任务，先拆成数据读取、受众判断、素材生成、预算测试、复盘五个输入/输出明确的任务，再串联验收。
- `V3_exclusivity`: passed — 单元必须只有一个动作，并明确材料、输出和检查条件；可替换的积木式流程是作者独特的执行视角。
- `source_refs`: candidates/frameworks.md:f04,f16；candidates/glossary.md:g07；candidates/principles.md:p042,p054-p055,p073；candidates/cases.md:c14,c19,c27

## v05｜双路需求证据法

- `type`: framework
- `merged_ids`: f05, g17, p014, p039, c18, c24, c35
- `V1_cross_domain`: passed — 搜索下拉词与帖子/评论挖掘（f05/c18）、低粉丝解决方案手册成交（c24）、跨赛道叙事复现（c35）对应“主动寻找”和“主动表达”两类证据。
- `V2_predictive_power`: passed — 要判断一个尚无产品的宠物服务需求时，先同时查搜索词和真实抱怨；只有单边信号时只做测试内容，不直接开发完整产品。
- `V3_exclusivity`: passed — 明确将搜索行为和发声行为作为两条独立证据链，避免把点赞或个人猜测当需求。
- `source_refs`: candidates/frameworks.md:f05；candidates/glossary.md:g17；candidates/principles.md:p014,p039；candidates/cases.md:c18,c24,c35

## v06｜人改 AI 的进化飞轮

- `type`: framework
- `merged_ids`: f06, p009, p015, p053, c25, c28, c42
- `V1_cross_domain`: passed — 错误日志写回规则（c08）、试看反馈重写手册（c25）、把说教改为个人经验（c42）覆盖 AI 协作、产品交付和内容表达。
- `V2_predictive_power`: passed — 当 AI 连续生成“正确但不像我”的销售文案时，保存人工改稿差异，抽取稳定的语气、取舍和禁用表达，下轮由规则先生成，再按新差异更新。
- `V3_exclusivity`: passed — 把“人改 AI”作为可记录的训练数据，并反哺规则/Skill，而不是一次性人工润色。
- `source_refs`: candidates/frameworks.md:f06；candidates/principles.md:p009,p015,p020,p052-p053,p055；candidates/cases.md:c08,c25,c28,c42

## v07｜最小闭环递增法

- `type`: framework
- `merged_ids`: f07, f13, g06, p018, p024, p031, p044, p059, p067, p068, p071, p077, c16, c31, c36, c41
- `V1_cross_domain`: passed — 搜索笔记起号（f07）、十条内容先卖知识库（c16）、先收款再交付（c31）、不会拍照也先发布（c36）分别验证内容、产品和能力不足场景。
- `V2_predictive_power`: passed — 面对一个尚未确定的课程方向，先发布一条解决具体问题的内容并收一笔可交付的订单，再决定课程结构；不先录完整课。
- `V3_exclusivity`: passed — “先跑一遍最小端到端闭环，再按反馈递增”同时约束产品、内容、设备和自动化投入。
- `source_refs`: candidates/frameworks.md:f07,f13；candidates/glossary.md:g06；candidates/principles.md:p018,p024,p031,p044,p059,p067-p068,p071,p077；candidates/cases.md:c16,c31,c36,c41

## v08｜反脆弱业务资产模型

- `type`: framework
- `merged_ids`: f08, g15, p005, p028, p033, p035, p065, p093, c29, c32, c50, c52, c54
- `V1_cross_domain`: passed — 平台规则变化后的虚拟电商（f08/c29）、内容同步到得物（c50）、闲置跨平台成交（c52）和供应商交付约束（c32/c54）体现产品、能力、关系、渠道的分离。
- `V2_predictive_power`: passed — 新平台突然限流时，先检查产品所有权、客户联系方式和交付能力是否仍在；若只有平台流量没有自有资产，优先迁移渠道而非继续加投。
- `V3_exclusivity`: passed — 将业务拆成“产品/能力/客户关系/渠道”，并要求前三者自有、渠道可替换，形成反脆弱而非平台依赖。
- `source_refs`: candidates/frameworks.md:f08；candidates/glossary.md:g15；candidates/principles.md:p005,p028,p033,p035,p065,p093；candidates/cases.md:c29,c32,c50,c52,c54

## v09｜需求验证三联法

- `type`: framework
- `merged_ids`: f09, f10, f11, f12, g03, g04, g05, p012, p022, p027, p032, p045, c12, c20, c22
- `V1_cross_domain`: passed — 耳机需求验证实验（c12）、人群问题到手册（c18）、低价资料升级为模板+批改（c22）、虚拟电商首品（c20）覆盖消费、知识产品和服务产品。
- `V2_predictive_power`: passed — 新建一个职场模板产品时，先锁定人群，再从搜索/评论确认问题，做一个可退换或可更新的最小版本，同时检查付费和交付可复制性；任一环节无证据则不扩张。
- `V3_exclusivity`: passed — 把需求验证固定为“搜索/评论—MVP—测试内容”三联证据，并增加需求、付费、交付三问。
- `source_refs`: candidates/frameworks.md:f09-f12；candidates/glossary.md:g03-g05；candidates/principles.md:p012,p022,p027,p032,p045；candidates/cases.md:c12,c18,c20,c22

## v10｜显性需求与潜在需求双层设计

- `type`: framework
- `merged_ids`: p016, p038, p048, c02, c34, c58, c59
- `V1_cross_domain`: passed — 搜索型手册/好物内容（c02/c24）、养生日历（c34）、单一解压玩具（c59）展示显性搜索需求和场景唤醒需求的不同入口。
- `V2_predictive_power`: passed — 对用户没有搜索但能被演示唤醒的收纳工具，先用场景演示测试潜在需求；对已有搜索词的报税服务，首屏直接回答问题，再设计转化。
- `V3_exclusivity`: passed — 用“正在需求/潜在需求”决定内容是承接搜索还是制造新认知，避免所有内容都按同一流量逻辑制作。
- `source_refs`: candidates/frameworks.md:f12；candidates/principles.md:p014,p016,p038-p039,p048；candidates/cases.md:c02,c24,c34,c58-c59

## v11｜不变逻辑—变化界面二层判断

- `type`: framework
- `merged_ids`: f15, p049, p050, p080, c07
- `V1_cross_domain`: passed — AI 工具选型（c07）、跨平台项目复制失败（c29）、AI 绘画题材切换（c64）均区分稳定需求逻辑与变化的工具/平台界面。
- `V2_predictive_power`: passed — 新 AI 产品改版后，不重学全部按钮，先保留“明确需求、输入背景、定义验收”的稳定层，只重新确认入口和限制。
- `V3_exclusivity`: passed — 把学习资源分成不变的需求表达/用户逻辑与可变的应用界面，指导快速变化环境中的投入顺序。
- `source_refs`: candidates/frameworks.md:f15；candidates/principles.md:p049-p050,p080；candidates/cases.md:c07,c29,c64

## v12｜元素级对标与热点生命周期法

- `type`: framework
- `merged_ids`: f17, f18, g09, g11, p023, p046, p056, p060, p074, c33, c38, c43
- `V1_cross_domain`: passed — 亲自仿制揭露拍摄壁垒（c33）、跨赛道话术复现（c35）、旅游迁移到婚摄（c45）、抄爆款只有点赞无转化（c38）覆盖样本拆解、迁移和时间阶段。
- `V2_predictive_power`: passed — 对一个昨日爆款，先判断其生命周期，再只提取情绪/结构等单一元素，结合自身素材小测；若样本已衰退或自身无法复制隐性壁垒，则不整篇照搬。
- `V3_exclusivity`: passed — “拆元素而非整账号”与“上升复刻、峰值换角度、尾声反向表达”的组合是明确的作者方法。
- `source_refs`: candidates/frameworks.md:f17-f18；candidates/glossary.md:g09,g11；candidates/principles.md:p023,p046,p056,p060,p074；candidates/cases.md:c33,c35,c38,c43,c45

## v13｜情境化精准提问与 AI 反问补全

- `type`: framework
- `merged_ids`: f19, f22, p057, c13
- `V1_cross_domain`: passed — 航海求助带数据（f19）、让 AI 反问缺口（f22）、思维模型映射场景（c13）、AI 设计人工搭建看板（c19）均以完整上下文换取可执行回答。
- `V2_predictive_power`: passed — 不知道如何向 AI 描述一次供应商筛选时，先让 AI 列出所需字段，再逐项补齐预算、交期、质量和约束，最后生成可验收的筛选表。
- `V3_exclusivity`: passed — 把提问变成“已做动作+样本+数据+异常+决策点”，并先让 AI 反问信息缺口，降低新手提示门槛。
- `source_refs`: candidates/frameworks.md:f19,f22；candidates/glossary.md:g17；candidates/principles.md:p042,p057；candidates/cases.md:c13,c19

## v14｜周期复盘—控制变量调整法

- `type`: framework
- `merged_ids`: f20, f23, f26, p040, p041, p047, p058, p083, p088, c37, c46, c49, c55
- `V1_cross_domain`: passed — 内容变量周复盘（f20/c37）、流量分层诊断（f23/f26）、投放按转化迁移预算（p083/c46/c49）覆盖自然内容和付费投放。
- `V2_predictive_power`: passed — 新账号连续低流量时，按固定观察窗口先排平台异常，再每周只改变一个变量并比较有效咨询/成交；不能把一次波动归因于算法。
- `V3_exclusivity`: passed — 将“玄学流量”转成变量层级诊断，并用固定周期、控制变量和有效成交指标作决策。
- `source_refs`: candidates/frameworks.md:f20,f23,f26；candidates/principles.md:p040-p041,p047,p058,p083,p088；candidates/cases.md:c29,c37,c43,c46,c49,c55

## v15｜网感盲测校准法

- `type`: framework
- `merged_ids`: f21, g10, p062
- `V1_cross_domain`: passed — 隐藏数据预测内容表现（f21）、跨赛道结构复现后的判断（c35）、延迟数据降低情绪干扰（c37）。
- `V2_predictive_power`: passed — 对一批未发布笔记，先隐藏账号、粉丝和历史数据，预测评论走向与成交意图，再用发布后一周数据校正；可预测选题是否适配，而不仅是复述爆款。
- `V3_exclusivity`: passed — “先盲测、后对答案、记录误差”把网感从自我感觉变成可训练的判断系统。
- `source_refs`: candidates/frameworks.md:f21；candidates/glossary.md:g10；candidates/principles.md:p062；candidates/cases.md:c35,c37

## v16｜先行动—遇题—解决反馈环

- `type`: framework
- `merged_ids`: f24, p069, p072, p089, c26, c57
- `V1_cross_domain`: passed — 不会拍照先发布（c36）、多项目分散后聚焦（c26/c57）、闲鱼出单后因售后退出（c54）展示先行动再根据真实摩擦调整。
- `V2_predictive_power`: passed — 对一个不确定的本地服务方向，只先完成一笔可撤销的小订单；客户真正提出交付、售后或获客问题后，再决定补能力或放弃。
- `V3_exclusivity`: passed — 用“行动产生真问题”替代“先把能不能做想清楚”，并以最小持续出摊形成反馈。
- `source_refs`: candidates/frameworks.md:f24；candidates/principles.md:p067-p069,p072,p077,p089；candidates/cases.md:c26,c36,c41,c54,c57

## v17｜先记录—再筛选内容法

- `type`: framework
- `merged_ids`: f25, g14, p070
- `V1_cross_domain`: passed — 生活碎片记录（f25/p070）、真实义乌经历转内容（c28）、个人过程替代说教（c42）。
- `V2_predictive_power`: passed — 先连续记录客户对产品的原话和失败片段，一周后按目标人群、问题和价值筛选成选题，能预测出哪些素材适合内容而不是即时凭灵感。
- `V3_exclusivity`: passed — 明确把采集与价值判断分离，允许素材先沉淀再按连接点重组。
- `source_refs`: candidates/frameworks.md:f25；candidates/glossary.md:g14；candidates/principles.md:p070；candidates/cases.md:c28,c42

## v18｜品类×场景×人设定位矩阵

- `type`: framework
- `merged_ids`: f27, f29, p004, p075, p076, p079, c39, c40
- `V1_cross_domain`: passed — 家居赛道能力不匹配（c39）、租房定位扩散（c40）、单一鲜明主题账号（c58）分别验证品类/场景、能力与一致性约束。
- `V2_predictive_power`: passed — 选择“职场工具”赛道时，列出品类、具体使用场景、目标人群、可提供价值、人设与视觉，删除无法持续表达或无法触达的象限，再测试一个定位。
- `V3_exclusivity`: passed — 不是抽象要求“找到定位”，而是用品类×场景坐标与赛道×用户×价值×人设×视觉五因子落格。
- `source_refs`: candidates/frameworks.md:f27,f29；candidates/principles.md:p004,p075-p076,p079；candidates/cases.md:c39,c40,c58

## v19｜变现目标倒推账号与产品—流量双路径

- `type`: framework
- `merged_ids`: f28, f30, p034, p037, p090, c44
- `V1_cross_domain`: passed — 低粉手册成交（c24）、虚拟电商低转高（c20）、陪跑产品化（c56）、粉丝与广告价值错位（c44）说明先定结果能约束前端人群与内容。
- `V2_predictive_power`: passed — 想做咨询业务时，先写清成交对象、交付结果和路径，再倒推账号吸引谁、内容讲什么；若只能带来不匹配粉丝，应停止追粉并改目标。
- `V3_exclusivity`: passed — 明确区分“拿产品找流量”和“拿流量找产品”两条起点，并让变现目标倒推账号设计。
- `source_refs`: candidates/frameworks.md:f28,f30；candidates/principles.md:p034,p037,p047,p090；candidates/cases.md:c02,c20,c24,c44,c56

## v20｜投放笔记赛跑与咨询质量反馈

- `type`: framework
- `merged_ids`: f31, f32, p081
- `V1_cross_domain`: passed — 多笔记并行测试再集中预算（f31/c46）、低价线索量大但成交少（f32/c49）、关键词少而精准（p081）覆盖投放测试和成交回传。
- `V2_predictive_power`: passed — 新广告账户先让多条内容以小预算赛跑，按有效咨询、成交和利润筛选；点击便宜但客户质量差的笔记不得加预算。
- `V3_exclusivity`: passed — 将“笔记赛跑”与后端咨询质量绑定，否定只看 CPC/咨询量的表面优化。
- `source_refs`: candidates/frameworks.md:f31-f32；candidates/principles.md:p040,p081,p083；candidates/cases.md:c46,c49

## v21｜反漏斗扩张模型

- `type`: framework
- `merged_ids`: f33
- `V1_cross_domain`: passed — 核心人群小范围验证再扩张（f33）、低价商品到后端服务（c20）、单一主题/单一产品内容（c58-c59）。
- `V2_predictive_power`: passed — 新产品先找十个高度匹配用户让其试用并反馈，再扩到兴趣人群，最后才做泛流量；若核心人群都不转化，不进入扩张阶段。
- `V3_exclusivity`: passed — 采用“核心人群→兴趣人群→拓展人群”的反漏斗顺序，把精准验证置于规模曝光之前。
- `source_refs`: candidates/frameworks.md:f33；candidates/principles.md:p031,p034,p038；candidates/cases.md:c02,c20,c34,c58-c59

## v22｜长期项目五项筛选与跨领域迁移

- `type`: framework
- `merged_ids`: f34, f35, g16, p013, p091, c30
- `V1_cross_domain`: passed — 多项目聚焦（c26/c57）、搬运资料转原创（c30）、既有经验产品化（f35/c56）覆盖项目选择、知识迁移和产品化。
- `V2_predictive_power`: passed — 评估一个新副业时，逐项检查已有成绩、独到方法、可复制、与主业关联、长期喜欢；通过后先迁移底层结构到具体项目并用结果验证。
- `V3_exclusivity`: passed — 将“喜欢”与“成绩/方法/复制/关联”放在同一筛选器中，并明确学习—定位—产品化—实证四步迁移链。
- `source_refs`: candidates/frameworks.md:f34-f35；candidates/glossary.md:g16；candidates/principles.md:p004,p013,p065,p075,p089,p091；candidates/cases.md:c26,c30,c57

## v23｜人机边界与原创信任规则

- `type`: principle
- `merged_ids`: p078, p086, p087, c47
- `V1_cross_domain`: passed — AI 初稿由人补判断（p009/p015）、客户客片在同意下协作生产（c47）、真实使用后分享（p086）和个人经验表达（c42）覆盖内容、测评、商业合作。
- `V2_predictive_power`: passed — 给 AI 生成一篇产品测评时，让 AI 做资料整理和初稿，但由人补真实使用、适用边界和不推荐对象；无法验证使用体验就不发布个人背书。
- `V3_exclusivity`: passed — 将“AI 做重复工作、人保留洞察、信任与身份表达”固化为可执行边界，并把原创与真实体验作为资产来源。
- `source_refs`: candidates/principles.md:p009,p015,p033,p053,p055,p078,p086-p087；candidates/cases.md:c28,c42,c47

## v24｜手动跑通后再自动化

- `type`: principle
- `merged_ids`: p026, p043, c23, c63
- `V1_cross_domain`: passed — 工具选型先试用（c07）、AI 设计后人工落地看板（c19）、快捷指令先解决自用采集（c23）、内容跨平台先低成本同步（c50）。
- `V2_predictive_power`: passed — 新自动化需求先手动完成三次并记录输入、异常和验收，再自动化稳定步骤；若手动路径仍不清楚，先不批量。
- `V3_exclusivity`: passed — “人先理解反馈、AI 后批量执行”把自动化门槛设在真实闭环之后，避免把不成熟流程放大。
- `source_refs`: candidates/principles.md:p018,p026,p043；candidates/cases.md:c07,c19,c23,c36,c50,c63

## v25｜产品分层与持续更新交付

- `type`: principle
- `merged_ids`: c21
- `V1_cross_domain`: passed — 十条内容标注更新中（c16）、低价到社群/服务（c20/c21）、资料包升级为批改服务（c22）、内容相邻日历产品（c34）。
- `V2_predictive_power`: passed — 设计一个新知识产品时，先用能负责交付的低价版本验证购买，再按用户阶段提供更新、服务和高价结果，避免把所有价值压在一份静态文件里。
- `V3_exclusivity`: passed — “边卖边做”与价格/用户阶段/交付深度分层结合，要求更新和反馈成为产品的一部分。
- `source_refs`: candidates/principles.md:p024,p031,p034-p035,p065；candidates/cases.md:c16,c20-c22,c34,c56

## v26｜用户兴趣先于合规引流

- `type`: principle
- `merged_ids`: p030, p092, c61
- `V1_cross_domain`: passed — 解决方案型内容先建立需求（c24）、内容—私信—成交链路（c46/c52）、平台规则与内容形式变化（c61）分别验证兴趣、路径与边界。
- `V2_predictive_power`: passed — 做一个新平台引流时，先发布能解决具体问题的内容并观察主动联系，再设计最短且用户知情的转化路径；任何需要规避平台规则的路径直接排除。
- `V3_exclusivity`: passed — 把引流前提定义为“用户想与作者建立联系”，同时把平台红线作为方法边界，而非只追求联系方式数量。
- `source_refs`: candidates/principles.md:p005,p030,p092-p093；candidates/cases.md:c24,c46,c52,c61

## v27｜高质量内容优先于设备与表面流量

- `type`: principle
- `merged_ids`: g08, g13, c67
- `V1_cross_domain`: passed — 低资源内容与高资源烂片对照（c67）、三万粉但广告价值低（c44）、产品即内容（g08）说明设备与泛流量不能代替场景价值。
- `V2_predictive_power`: passed — 预算有限时先用现有设备发布能解决具体问题的内容，以有效咨询/成交判断瓶颈；只有内容价值已被证明且设备确实限制表达时才升级。
- `V3_exclusivity`: passed — 将“内容价值、具体场景、有效求购信号”置于设备、粉丝和泛点赞之前，形成结果导向的资源排序。
- `source_refs`: candidates/principles.md:p038,p040,p047-p048,p071,p077；candidates/glossary.md:g08,g13；candidates/cases.md:c37,c44,c67

## v28｜合规与可撤销风险控制

- `type`: principle
- `merged_ids`: p002, p003, p019, p082, p084, p085, c10, c11
- `V1_cross_domain`: passed — 同步凭据与权限边界（p002-p003）、健康决策交叉医生意见（c11）、可退货耳机实验（c12）、商用客片授权（c47）覆盖数据、安全、健康、商业合作。
- `V2_predictive_power`: passed — 面对一个涉及账号权限、健康建议或商用素材的自动化任务，先标出不可逆风险，限制授权范围，要求专业/权利确认；不确定时暂停而不是默认执行。
- `V3_exclusivity`: passed — 把“可逆实验、人工确认、授权边界、专业交叉验证”组合成行动前风险门，而不是泛泛提醒小心。
- `source_refs`: candidates/principles.md:p002-p003,p019,p041,p082,p084-p085,p093；candidates/cases.md:c10-c12,c47,c54
