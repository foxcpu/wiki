# 操作日志

## [new] ingest|摄入《AI大模型合规指南（合规99问）》（Aiii人工智能创研院，2026-07）

- 创建 source-summary: `sources/2026-07-22-AI大模型合规指南-合规99问-白皮书`
- 创建 narrative analysis: `analysis/2026-07-22-AI大模型合规指南-合规99问-叙事解读`
- 创建概念页: `concepts/AI合规.md`
- 更新 wiki/index.md: 添加资料摘要（前置）、分析条目（前置）、概念条目
- 更新 log.md: 追加记录
- **定位**: 本知识库首份系统性合规文献，与现有的AI工程实践（Harness/Agent）形成互补，从法规与伦理维度补充AI落地的另一关键维度
- **强化**:本文为 [[Agent-Control-Plane]] 从"技术控制"延伸到"合规控制"提供了完整框架——算法备案、第三方审计、透明度报告都是控制面的合规维度；为 [[Harness-Engineering]] 补充了供应链安全与模型权重保护的技术要求（Q26/Q29）
- **互补**:与 [[Problem-First-AI-Adoption]] 形成「技术落地+合规落地」的双轨互补——AI落地不仅是找到问题优先的场景，还需要满足该场景的合规要求；与 [[Vibe-Engineering]] 形成「伦理委员会」概念的完整补充
- **校准**:将"AI合规"从零散法规清单校准为系统性的十大领域框架——伦理与社会责任、法律责任与风险、安全技术与防护、行业应用合规、跨境与全球合规、用户权益与隐私保护、知识产权、内容合规、算法治理、训练数据合规
- **矛盾/待观察**:
  1. 中国《生成式人工智能服务管理暂行办法》的实际执法力度与案例尚未充分积累
  2. 欧盟AI Act的正式实施细节与高风险系统认定标准仍在细化
  3. AI产品责任的司法实践判例尚不丰富，"发展风险抗辩"边界待明确
  4. 训练数据"被遗忘权"的技术可行性仍是开放问题
  5. 各主要市场的监管差异带来的合规成本对中小企业的影响

## [new] compile|整合《以慢人生定力》至知识库（2026-06-18）

### 使用 llm-wiki skill 执行整合

**创建实体页（5个）：**
- `entities/姜澜.md` — 演讲者，北京理工大学校领导
- `entities/王淦昌.md` — 两弹一星功勋科学家；"科学没有国界，但科学家有祖国"
- `entities/董海山.md` — 含能材料院士；"一辈子没有做过重大原始性创新"
- `entities/王海福.md` — 活性毁伤技术院士；二十年铸成国之重器
- `entities/北京理工大学.md` — "双一流"高校

**创建概念页（1个）：**
- `concepts/定力.md` — AI 时代三种定力（家国/内心/沉潜）+ 三个慢；含 Mermaid 图、四层境界表、金句；与 Result-Certainty/Cognitive-Offloading 关联

**更新现有页面：**
- `concepts/Result-Certainty.md` — 添加与定力的关联（主观稳定性 vs 客观可验证路径）
- `concepts/Cognitive-Offloading.md` — 添加与定力的关联（价值观层面）以及相关引用

**更新 index.md：**
- 人物条目新增：姜澜、王淦昌、董海山、王海福
- 社区/组织新增：北京理工大学
- 概念新增：定力

**关联分析：**
- 定力 ←→ Result-Certainty：[[定力]] 解决"人如何在 AI 时代不随波逐流"，Result-Certainty 解决"AI 协作如何确保结果正确"
- 定力 ←→ Cognitive-Offloading：定力是认知外包在价值观层面的解毒剂

## [new] ingest|摄入《以慢人生定力，驭快智能时代》（姜澜，北京理工大学，2026-06-18）
- 创建 source-summary: `sources/2026-06-18-姜澜-以慢人生定力驭快智能时代`
- 创建 narrative analysis: `analysis/2026-06-18-姜澜-以慢人生定力驭快智能时代-叙事解读`
- 更新 wiki/index.md: 添加资料摘要、分析条目
- 更新 log.md: 追加记录
- **主题**: 毕业典礼致辞，核心命题"工具可以快，成长不能急"
- **三种定力**: 家国定力（王淦昌/十七年隐姓埋名/科学无国界科学家有祖国）、内心定力（算法陷阱/四层境界/董海山"一辈子没有做过重大原始性创新"）、沉潜定力（王海福/七年才拿到基金/二十年铸成国之重器）
- **三个慢**: 慢思考（独处理解/深度思考）、慢积累（难路即快路）、慢坚守（向下扎根/时间磨砺精彩）
- **关联**: 与本知识库AI主题形成互补——当众人追求AI提速时，这篇致辞提供了一剂"减速"的哲学思考；三种定力与[[concepts/Result-Certainty]]（结果确定性）可形成方法论互补

## [11:00] ingest|摄入《告别"氛围编程"：基于Harness治理和SDD的团队级AI研发范式演进与实践》（阿里云开发者，2026-06-15）
- 创建 source-summary: `sources/2026-06-15-告别氛围编程：基于Harness治理和SDD的团队级AI研发范式演进与实践`
- 创建 narrative analysis: `analysis/2026-06-15-告别氛围编程-叙事解读`
- 更新 wiki/index.md: 添加资料摘要（前置）、分析条目（前置）
- 更新概念页: Harness-Engineering、SDD、Vibe-Coding（新增源引用）
- 更新 log.md: 追加记录
- **强化**:本文是 [[Harness-Engineering]] 和 [[SDD]] 从"概念框架"到"阿里内部 Qoder 平台完整落地"的工程化实现。SDD 四阶段工作流（Specify→Plan→Implement→Validate）与 Harness 四支柱（上下文工程/架构约束/反馈回路/人类监督）形成完整的"规范驱动+工程治理"框架。
- **互补**:与 [[sources/2026-06-15-QQ音乐Harness Engineering实践]] 形成"为什么需要 Harness"（QQ 音乐）→ "如何用 SDD+Harness 实现"（本文）的互补叙事；与 [[sources/2026-06-15-卡帕西：从"氛围编码"到"代理工程"的AI演进]] 形成"代理工程概念 → 中国大厂内部落地"的互补；与 [[sources/2026-05-22-代码一旦生产出来首先是负债-一个CIO的AI效能实践复盘]] 形成"哲学层面 → 全链路工程实现"的互补。
- **校准**:将"出码率"从成果指标校准为过程指标——出码率高不等于提效，真正的提效需要全链路闭环；将"Vibe Coding 适用范围"从"新项目/小脚本"扩展到"存量应用风险极高"；将"人类角色"从"代码编写者"校准为"需求定义者、规范审核者、结果验证者"。
- **矛盾/待观察**:
  1. Qoder 平台是阿里内部工具，实践是否可以迁移到 Claude Code/Cursor 等通用工具需要验证
  2. 专家团模式在跨团队大型项目中的协作机制尚未详细展开
  3. 知识库三层结构的维护成本——随着项目规模增长，文档同步成本如何控制
  4. Spec 质量依赖人工干预（HITL），人工成本在复杂项目中是否可接受

## [10:30] ingest|摄入《QQ音乐Harness Engineering实践》（QcloudCommunity，2026-06-15）
- 创建 source-summary: `sources/2026-06-15-QQ音乐Harness Engineering实践`
- 创建 narrative analysis: `analysis/2026-06-15-QQ音乐Harness Engineering实践-叙事解读`
- 更新 wiki/index.md: 添加资料摘要（前置）、分析条目（前置）
- 更新概念页: Harness-Engineering（新增「企业级落地」完整章节：核心公式/五类上下文缺口/四类业务约束/五阶段四门禁/三仓联动/服务矩阵/三层知识/Self-Refinement/L5治理层）
- 更新 log.md: 追加记录
- **强化**:本文是 [[Harness-Engineering]] 从「三支柱/四维度/五特征」到「五阶段+四门禁+三仓联动+三层知识+Self-Refinement」的完整企业级落地实现；为 [[SDD]] 补充了"需求→设计→开发→交付全链路门禁"的流程治理维度；为 [[Vibe-Coding]] 的"崩溃模式"提供具体企业级工程化解决路径
- **互补**:与 [[sources/2026-06-09-AISE-Harness-技术调研报告]] 形成「技术底层控制模式 → 工程治理层具体实现」的互补；与 [[sources/2026-05-05-Harness-Engineering-手册前言]] 形成「手册方法论 → 真实业务落地」的互补；与 [[sources/2026-06-15-卡帕西：从"氛围编码"到"代理工程"的AI演进]] 形成「为什么需要代理工程 → 如何实现代理工程」的互补
- **校准**:将"Harness Engineering"从"系统级基础设施"校准为"可以按需采纳的分层结构"——五阶段/四门禁/三层知识都是可选组件；将"AI协作效率"从"生成速度"校准为"端到端交付效率"；将"上下文工程"从"提示词优化"校准为"知识即资产"
- **矛盾/待观察**:
  1. 五阶段+四门禁在50+微服务规模下运转良好，但在3~5人小团队的适用性尚待验证
  2. 三仓联动对CI/CD流程和团队协作习惯要求较高，迁移成本如何
  3. .service-matrix/dependencies.yaml作为单一真相源需持续维护，服务拓扑变化时如何确保及时同步
  4. L5治理层包含34 Skills/24 Agents/35 Commands，维护成本不容忽视——小型团队是否有能力维持这套体系
  5. 占位符系统（{business-repo}/{idl-repo}）在跨团队共用同一Harness仓时是否会产生命名冲突或歧义

## [09:12] ingest|摄入《卡帕西：从"氛围编码"到"代理工程"的AI演进》（2026-06-15）
- 创建 source-summary: `sources/2026-06-15-卡帕西：从"氛围编码"到"代理工程"的AI演进`
- 创建 narrative analysis: `analysis/2026-06-15-卡帕西：从"氛围编码"到"代理工程"的AI演进-叙事解读`
- 创建实体页: Andrej-Karpathy（斯坦福博士、特斯拉前自动驾驶视觉主管、AI教育者；「软件3.0」「代理工程」概念提出者）
- 创建概念页: 代理工程（Agentic Engineering，与"氛围编码"对照的新兴工程学科）
- 更新 index.md: 添加资料摘要（前置）、分析条目（前置）、人物条目、概念条目
- 更新 log.md: 追加记录
- **强化**:本文为 [[Vibe-Coding]] 从"降低门槛"到"质量保障"提供了理论锚点——卡帕西明确区分"氛围编码"(让每个人编程)和"代理工程"(维持专业质量)；为 [[Vibe-Engineering]] 补充了"代理系统是统计模拟而非真正智能"的核心认知
- **互补**:与 [[Harness-Engineering]] 形成"软件3.0时代的新工程学科"互补——Harness是工程实践，代理工程是更高层的设计哲学；与 [[Agent-Self-Drive]] 形成"代理特性认知"的互补——卡帕西强调"不能用对待人的方式对待代理"
- **校准**:将"AI编程的未来"从"人人都是程序员"校准为"两极分化"——氛围编码降低入门门槛但稀释质量，代理工程提升专业效率但需要新工程能力；将"招聘代理工程师"从"算法题"校准为"大型项目实施经验"
- **矛盾/待观察**:
  1. "代理工程"作为新工程学科，其具体实践方法论尚待社区沉淀
  2. 可验证性(Verifiability)概念的边界——哪些领域的输出可以被明确验证？这些边界会随模型能力变化吗？
  3. 人类理解作为"最后堡垒"——这个判断是否会随着AI在理解层面的进步而过时？

## [18:00] write|创作《当 AI 产品遇上 CEO 意志驱动》（2026-06-12）
- 创建 source-summary: `sources/2026-06-12-当AI产品遇上CEO意志驱动`
- 创建 narrative analysis: `analysis/2026-06-12-当AI产品遇上CEO意志驱动-叙事解读`
- 更新 index.md: 添加资料摘要和分析条目
- **定位**: 面向 PM 从业者的行动镜鉴，综合《置身钉内》、蒋林泉复盘、Uber Bloomberg 报道
- **强化**:本文与 [[analysis/2026-06-12-公司導入AI為何無效工作反而變多-叙事解读]]（KPI 剧场）形成姐妹篇——KPI 剧场聚焦"组织追逐指标"，本文聚焦"CEO 意志扭曲产品方向"，共同指向古德哈特定律在 AI 时代的不同变体；是 [[Problem-First-AI-Adoption]] 从"组织变革路径"到"PM 微观决策困境"的微观落地

## [17:00] ingest|摄入《公司導入AI，為何無效工作反而變多？》（黃昭瑛，商业周刊，2026-06）
- 创建 source-summary: `sources/2026-06-12-公司導入AI為何無效工作反而變多`
- 创建 narrative analysis: `analysis/2026-06-12-公司導入AI為何無效工作反而變多-叙事解读`
- 创建实体页: 黃昭瑛（商业周刊管理频道专栏作者，聚焦企业 AI 转型与 KPI 表演现象）
- 创建概念页: 古德哈特定律（当一个指标成为目标，它就不再是一个好指标；AI 时代新指标的特殊脆弱性）
- 更新 index.md: 添加资料摘要（前置）、分析条目（前置）、人物条目、概念条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Harness-Engineering]] 从「真实价值闭环」到「KPI 表演陷阱」的反面教材——当指标成为目标而非真实价值，Harness 闭环失效；是 [[Agent-Self-Drive]]「先定义成功」原则的反面——结果导向被替换为指标导向
- **互补**:与 [[Problem-First-AI-Adoption]] 形成「KPI 驱动 vs 问题优先」的互补——本文揭示「集邮癖」在 AI KPI 场景的具体表现；与 [[North-Star-Metric]] 形成「假北极星 vs 真北极星」的对照
- **校准**:将「AI 落地进度」从「Token/Skill 数量」校准为「时间节省、效率提升、质量改善」等可量化业务价值；将「AI 转型焦虑」从「必须做点什么」校准为「真正转型很慢，涉及系统性变革」
- **矛盾/待观察**:
  1. 如何区分「KPI 表演」与「真实但量小的价值创造」——那些只做了一个但每天被使用的 Skill，如何被组织认可？
  2. 古德哈特定律在 AI 场景下是否有特殊表现——Token 消耗量这类新指标是否比传统 KPI 更难避免被扭曲？
  3. 企业如何建立真正有效的 AI 价值衡量机制，而非用「容易统计」代替「真正重要」？

## [16:30] ingest|摄入《通才配AI，压过领域专家》（鸭哥，2026-06-09）

- 创建 source-summary: `sources/2026-06-09-通才配AI-压过领域专家`
- 创建 narrative analysis: `analysis/2026-06-09-通才配AI-压过领域专家-叙事解读`
- 更新 index.md: 添加资料摘要（前置）、分析条目（前置）
- 更新 log.md: 追加记录
- **强化**:本文为 [[Harness-Engineering]] 从「上下文工程/架构约束/持续治理」到「控制和校准层」的范式延伸——稻瘟病实验证明「校准AI的人」比「领域专家」更稀缺；advisor tool 证明权责分离架构（工具收走/控制权收走/只能以建议文本注入回路）是从源头消除强模型越界风险的最优解
- **互补**:与 [[sources/2026-06-09-AISE-Harness-技术调研报告]] 形成「控制模式理论 → 人机校准实践」互补；与 [[sources/2026-06-12-Uber-AI-budget-cap]] 形成「AI能力越强 → 控制层越值钱」的延伸；与 [[sources/2026-05-02-How-AI-Impacts-Skill-Formation]] 形成「AI拉平领域知识 vs 校准知识稀缺」的镜像
- **校准**:将「AI时代稀缺什么」从「领域知识」校准为「校准AI的能力」——前者分散（三百六十行各一道门槛），后者可迁移（模型毛病各领域长得差不多：过度乐观/编造数据/低估复杂度/不主动停下来）；将「定价围栏」从「价目表策略」校准为「推理循环内的实时分箱」——Anthropic classifier 在每次调用瞬间重新分一次箱
- **矛盾/待观察**:
  1. 稻瘟病实验的样本量（6位博士/3次重复）是否足够支撑「通用组系统性优于专家组」的强结论
  2. 「校准知识可迁移」的前提是模型失败模式的跨领域相似性——随着模型能力提升，这一相似性是否会被打破
  3. Anthropic Fable 5 退出订阅后，按用量计费的真实成本是否会倒逼企业重新审视 advisor tool 模式
  4. DeepSeek V4-Pro 降价75% 与 Anthropic Fable 5 涨价形成价格战光谱，对中间市场用户的策略选择影响待观察

## [15:30] ingest|摄入《Lovable 14个月从0做到4亿美元》+《AI安全扫描器被JavaScript注释绕过》（鸭哥，2026-06）

- 创建 source-summary: `sources/2026-06-12-Lovable-14个月从0做到4亿美元`
- 创建 narrative analysis: `analysis/2026-06-12-Lovable-4亿美元与AI安全扫描器叙事解读`
- 创建实体页: Lovable（UGS 平台，14个月 ARR $400M，95% 个人订阅，credit 定价结构性矛盾）、Bolt.new（同期 UGS 竞品）
- 更新概念页: Agent-Control-Plane（新增「credit 定价：轻量级个人层的治理原型」小节，Lovable credit 墙与 Uber $1,500 上限形成光谱两端）
- 更新概念页: Model-Commoditization（新增「token 价格战：从理论到实战」完整小节，OpenAI vs Anthropic 降价信号 / Goldman Sachs token 消耗增速数据 / Tokenpocalypse / IPO 冲刺）
- 更新概念页: Vibe-Coding（新增「UGS：Vibe Coding 的独立商业品类」完整小节，Lovable 商业账本验证 / credit 定价缺陷 / 原型→生产价值流向 B2D 工具）
- 更新 index.md: 添加资料摘要（前置）、分析条目（前置）、产品/模型实体（Lovable/Bolt.new）
- 更新 log.md: 追加记录
- **强化**:本文为 [[Agent-Control-Plane]] 从"企业预算配额"延伸到"个人即付即用 credit"提供了轻量级治理原型；为 [[Model-Commoditization]] 从"能力趋同"到"成本压力"的演进提供量化数据；为 [[Vibe-Coding]] 添加 UGS 作为首个商业账本验证的独立品类
- **互补**:与 [[sources/2026-06-12-Uber-AI-budget-cap]] 形成"企业预算硬控 vs 个人 credit 即付即用"互补，两者共同构成 agentic 经济模型的完整光谱（$1,500/人/月 → $20/月 credit → 按次幻觉计费）
- **校准**:将"AI 商业化成功"从单一维度（ARR 数字）校准为"商业模型 vs 用户价值的匹配度"——Lovable 95% 个人用户但 5% 企业收入说明重度用户留不住，价值流向 B2D 工具；将"安全扫描器被绕过"从"具体攻击技术"校准为"安全机制场景错配的系统性问题"
- **矛盾/待观察**:
  1. UGS 品类的快速增长是否会在 2026 下半年催生定价模型演进（按功能/按产出而非按 token 计费）
  2. 重度用户持续外流是否会压低个人用户留存率，最终影响 ARR 增长曲线
  3. Anthropic 隐蔽降能机制从道歉到撤回的快速响应是否代表内部安全文化成熟，还是迫于舆论压力
  4. LLM 安全扫描器的场景错配问题是否已被主流厂商纳入修复路线图
  5. OpenAI 和 Anthropic IPO 冲刺是否会成为 UGS/B2D 工具竞争格局的决定性变量

## [14:00] ingest|复核补全《How a non-technical project manager built and shipped a stress management app with Claude Code in six weeks》（Anthropic Day zero，2026-06）
- 本次为**复核与补全会话**：source-summary / narrative analysis / 实体页已在上次会话（[10:30] Uber 条目前）完整创建，本次验证并补充以下遗漏内容：
- 更新概念页: [[Agent-Self-Drive]]（新增「非技术创始人的结果导向：Respiro 案例」完整小节：Vlasenko 案例作为"先定义成功+结果导向"的极端样本，创始人即目标用户充当质量替代机制）
- 更新概念页: [[Multi-Model-Orchestration]]（新增「个人项目级别的多 Agent 并行：Respiro」完整小节：15+ specialist Agent 并行架构、TCA 架构师/Swift 开发/Metal 专家/代码审查员等角色表、与企业级多模型编排的差异分析）
- 更新概念页: [[Vibe-Engineering]]（新增「个人副业项目的最小 Vibe Engineering 样本」完整小节：Vlasenko vs 黄东旭头狼模式对比表、个人级组织形态的意义与待验证问题）
- 更新实体页: [[Anthropic]]（新增「客户端采纳的非技术用户标杆」完整小节：Respiro 案例与 Uber 预算上限案例形成对照，Anthropic 客户端战略同时向"下限拓展"与"上限承压"两个方向演进）
- **强化**:Respiro 案例从此前已更新的 Vibe-Coding / Claude-Code 进一步渗透到 Agent-Self-Drive / Multi-Model-Orchestration / Vibe-Engineering三个概念页，覆盖"自驱闭环/多 Agent 编排/组织形态"三个维度
- **互补**:与 Uber 案例（企业上限）形成「个人无限实验 vs 企业成本约束」的双向对照，完整覆盖 Claude Code采纳光谱的两端
- **矛盾/待观察**:15+ Agent 并行但缺少 spec 锚定/测试验证机制，长期工程质量与企业级 Harness 要求仍有距离；非技术创始人如何识别 Agent 系统性盲区仍是开放问题

## [10:30] ingest|摄入《Uber Caps Usage of AI Tools Like Claude Code to Cut Costs》（Bloomberg，2026-06）
- 创建 source-summary: `sources/2026-06-12-Uber-Caps-Usage-of-AI-Tools-Like-Claude-Code-to-Cut-Costs`
- 创建 narrative analysis: `analysis/2026-06-12-Uber-AI-budget-cap-叙事解读`
- 创建实体页: Uber（网约车与配送平台，AI 预算超支后限制员工使用 agentic coding 工具）、Walmart（零售巨头，被报道限制内部 AI agent 使用）
- 更新实体页: Anthropic（新增“企业采纳的成本反噬”小节：Uber 案例对客户端战略的双面信号）、Claude-Code（新增“企业预算约束信号：Uber 使用上限”小节）、Cursor（新增“企业预算约束：Uber 使用上限”小节）
- 更新概念页: Agent-Control-Plane（新增“预算与配额：成本治理作为控制面新维度”完整小节，将注册/身份/权限/审计/预算串为控制面五维）、Vibe-Coding（新增“企业规模化成本现实：从无限实验到预算上限”完整小节）
- 更新 index.md: 添加资料摘要、分析、公司条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Agent-Control-Plane]] 从“身份/权限/审计”向“预算与配额治理”延伸的鲜活企业案例；将 [[Vibe-Coding]] 的规模化边界从技术/组织拓展到财务硬约束
- **互补**:与 [[sources/2026-06-12-How-a-non-technical-project-manager-built-Respiro-with-Claude-Code]] 形成「个人/副业无限实验 vs 大企业预算硬约束」互补；与 [[sources/2026-05-22-代码一旦生产出来首先是负债-一个CIO的AI效能实践复盘]] 形成「美国互联网公司预算配额硬控 vs 中国大厂组织变革控成本」互补
- **校准**:将“AI 写代码比例”从成果指标重新定位为投入指标；将 agentic 工具从“无限使用/鼓励实验”重新定位为需要配额管理的生产资源；将企业 AI 采纳焦点从技术渗透率重新定位为投入产出与预算纪律
- **矛盾/待观察**:
  1. Uber 10% AI 代码比例的业务价值、缺陷率、维护成本均未披露，高比例不等于高价值
  2. 1,500 美元/人/月上限对高频工程师是否足够，若超额申请泛滥则上限流于形式
  3. Uber 因 AI 收益放缓招聘，但 COO 又表示难见消费者功能增量——“降本”与“增效”证据强度不对称
  4. Walmart 等企业的同步动作是否预示 2026 下半年会出现一轮“agentic AI 预算紧缩周期”，进而冲击工具厂商订阅与 seat 模式
  5. 发言人把配额包装为“负责任地鼓励采纳”，但其直接动因是预算超支——企业如何在鼓励实验与财务纪律间取得平衡尚无成熟模板

## [09:00] ingest|摄入《置身钉内》（钉钉前产品经理幽素对 AI 项目 ONE 的亲历复盘，2026-06）
- 创建 source-summary: `sources/2026-06-04-置身钉内`
- 创建 narrative analysis: `analysis/2026-06-04-置身钉内-叙事解读`
- 创建实体页: 钉钉（阿里巴巴集团企业协同平台，ONE 与悟空的母公司/产品底座）、无招（钉钉创始人，ONE 项目关键决策者）、阿里巴巴（ONE/悟空所属集团）、飞书（字节跳动企业协同产品，悟空竞品参照）、企业微信（腾讯企业协同产品，悟空竞品参照）、ONE（钉钉 2025-2026 年 AI 工作信息流/专属秘书项目）、悟空（2026 年替代 ONE 的企业级 AI 工作平台）
- 更新概念页: Problem-First-AI-Adoption（新增「反面案例：当 AI 先于问题」小节，以 ONE 项目说明发心混杂/定位摇摆/用户失真/场景错配如何导致「非问题优先」）
- 更新概念页: Agent-Self-Drive（新增「反面教训：成功标准被替换为外部指标」小节，以 ONE 项目说明验收标准异化为可汇报指标的风险）
- 更新概念页: Vibe-Engineering（新增「组织形态的反例：大公司的 Vibe 困境」小节，对比 ONE 大组织模式与黄东旭头狼+狼群模式）
- 更新 index.md: 添加资料摘要、分析、人物/公司/产品条目
- 更新 log.md: 追加记录
- **强化**:本文以一手亲历复盘为 [[Problem-First-AI-Adoption]]、[[Agent-Self-Drive]]、[[Vibe-Engineering]] 三个概念页提供了大型企业内部的真实反面样本；将「发心」「已读恐怖主义」「每日一包」「共创失真」等具象概念沉淀为可复用的分析透镜
- **互补**:与 [[sources/2026-04-06-马工-别学AI了直接用起来]] 形成「中小企业问题优先路径 vs 大组织非问题优先反例」互补；与 [[sources/2026-01-20-当前关于Vibe-Engineering的所有认知都会在1个月内严重过时]] 形成「精英个体头狼模式 vs 大公司组织消耗」互补
- **校准**:将「AI 产品失败」从「技术/模型不够强」校准为「发心混杂、组织形态、指标扭曲」等结构性因素；将「快速迭代」从无条件正确重新定位为依赖组织环境——大组织的「每日一包」反而加速方向摇摆
- **矛盾/待观察**:
  1. 作者身份为「前产品经理」，复盘带有亲历者视角，部分判断（如无招决策风格、组织压力）是否需要更多内部交叉验证
  2. 悟空在 2026 年 4 月后替代 ONE 入口，其实际产品表现与用户反馈尚未有独立第三方数据
  3. ONE 的「卡片流」形态失败是否完全归因于「非问题优先」，还是也受到钉钉生态位、市场竞争时机等外部因素制约

## [08:55] ingest|摄入《代码一旦生产出来，首先是负债 —— 一个CIO 的AI效能实践复盘》（阿里云 CIO 蒋林泉，2026-05）
- 创建 source-summary: `sources/2026-05-22-代码一旦生产出来首先是负债-一个CIO的AI效能实践复盘`
- 创建 narrative analysis: `analysis/2026-05-22-代码一旦生产出来首先是负债-一个CIO的AI效能实践复盘-叙事解读`
- 创建实体页: 蒋林泉（阿里云 CIO，「技能通胀，品味通缩」「代码一旦生产出来首先是负债」提出者）
- 创建实体页: 阿里云（阿里巴巴集团云计算与人工智能科技公司，CIO 线 AI 产研效能规模化实践主体）
- 创建概念页: Code-as-Liability（代码即负债：生产代码首先视为负债，价值需经业务闭环验证）
- 创建概念页: Half-Stack（Half-Stack 岗位设计：PDFE/ABE 两类端到端角色，用 AI 降低跨域门槛）
- 更新概念页: Vibe-Coding（新增「企业规模化边界」小节：Demo/新应用 vs 存量生产系统、阿里云 CIO 线选择、Live Demo 需求澄清前置）
- 更新概念页: Harness-Engineering（新增「企业规模化实证：阿里云 CIO 线」小节：四个左移动作、Half-Stack 组织维度、对 AI 生码率指标的校准）
- 更新概念页: SDD（新增「从存量代码还原 Spec」小节：多源挖掘、规约化模板、Spec 腐化的反向观察）
- 更新概念页: Intent-Alignment（新增「需求澄清前置：Live Demo 作为意图对齐载体」小节）
- 更新概念页: Product-Tri-Ownership（新增「与 Half-Stack 的对比」小节）
- 更新 index.md: 添加资料摘要、人物、公司、概念、分析条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Vibe-Coding]] 从「个人/精英实践」到「企业规模化边界」的关键校准；是 [[Harness-Engineering]] / [[SDD]] / [[Intent-Alignment]] 在大中型企业存量系统中的完整实证；将 [[Code-as-Liability]] 从金句推进为可操作软件工程哲学
- **互补**:与 [[Product-Tri-Ownership]] 形成「拆分超级个体（PO/QO/TO）vs 合并岗位（PDFE/ABE）」的团队规模化路径互补；与 [[sources/2026-04-09-The-Enterprise-AI-Playbook]] 形成「中国大厂产研组织重构 vs 跨国跨行业制度证据」互补；与 [[sources/2026-01-20-当前关于Vibe-Engineering的所有认知都会在1个月内严重过时]] 形成「精英个体多 Agent 协同 vs 企业级组织变革」互补
- **校准**:将「AI 生码率」从成果指标重新定位为过程指标/管理陷阱；将「Vibe Coding」从万能入口重新定位为有边界的工具（适合 Demo/新应用需求澄清，不适合存量生产系统直落）；将「左移」从「正确但昂贵」重新定位为 AI 时代 ROI 为正的核心策略；将「全栈工程师」从理想目标重新定位为「例外而非解法」
- **矛盾/待观察**:
  1. 阿里云 CIO 线数据来自内部统计，缺乏独立第三方验证；3x/2x 代码量提升是否伴随同比例业务价值提升未披露
  2. Half-Stack 岗位（PDFE/ABE）与传统职能边界冲突，是否会导致专业人才招聘/培养难度上升、职业发展路径模糊
  3. 「代码首先是负债」与 Vibe Coding 快速产出 Demo 的倡导之间存在张力——如何在鼓励快速验证与警惕负债之间取得平衡
  4. 蒋林泉认为「AI 只能做到 average」，与部分企业宣称 AI 已能替代高级工程师的说法不一致；两种判断的边界条件（任务类型/系统复杂度/验收标准）有待明确
  5. Spec 维护成本「反而下降」的观察基于 AI 生成代码更规整的假设，在高度遗留、异构代码库中是否成立仍需验证
  6. 测试覆盖率「加权接近 100%」中的「加权」口径未解释，不同项目/团队间的可比性不明

## [当前] ingest|摄入《How a non-technical project manager built and shipped a stress management app with Claude Code in six weeks》（Anthropic Day zero 创始人故事，2026-06）
- 创建 source-summary: `sources/2026-06-12-How-a-non-technical-project-manager-built-Respiro-with-Claude-Code`
- 创建 narrative analysis: `analysis/2026-06-12-Respiro-故事-非技术PM如何用Claude-Code六周上架App-Store`
- 创建实体页: Kostiantyn-Vlasenko（Mythical Games 十年项目经理、Respiro 创始人，零代码基础六周上架 App Store）
- 创建实体页: Respiro（iOS 科学压力管理应用，实时检测压力信号并主动推送引导式呼吸练习）
- 创建实体页: Mythical-Games（Vlasenko 长期任职的游戏工作室，AI 编程工作流回渗样本）
- 更新实体页: Claude-Code（新增“非技术 PM 独立上架 Respiro”标杆案例小节）
- 更新概念页: Vibe-Coding（新增“非技术创始人的边界拓展”完整小节：Vlasenko 模式对比表、关键信号、可复制性与待观察问题）
- 更新 index.md: 添加资料摘要条目、新增人物/公司/产品条目、添加 narrative analysis 条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Vibe-Coding]] 概念页从“会写代码的人用 AI 加速”到“完全不会写代码的人也能独立交付上架产品”的边界拓展；为 [[Agent-Self-Drive]] 提供“先定义成功 + 结果导向”的极端案例；15+ 专业子 Agent 并行为 [[Multi-Model-Orchestration]] / [[Vibe-Engineering]] 提供具体个人实践样本
- **互补**:与 [[sources/2026-01-20-当前关于Vibe-Engineering的所有认知都会在1个月内严重过时]] 形成「精英开发者头狼模式 vs 零基础 PM 的 Agent 管理」互补；与 [[sources/2026-05-02-How-AI-Impacts-Skill-Formation]] 形成「非技术者借助 AI 完成原本需要多年技能积累的任务」互补；与 [[sources/2026-04-09-The-Enterprise-AI-Playbook]] 形成「个人副业原型 vs 大企业制度部署」互补
- **校准**:将 Claude Code 的“使用门槛”从“需要会编程”校准为“需要会管理复杂目标”；将 Vibe Coding 的“失败风险”从“代码质量问题”校准为“非技术用户需要大量界面导航/第三方服务/上架流程的辅助”——视觉能力是关键；将“多 Agent 协作”从“大厂/精英开发者专属”校准为“个人副业项目即可使用”
- **矛盾/待观察**:
  1. Vlasenko 案例的可复制性：十年项目管理经验、明确个人痛点、充裕业余时间三者缺一不可
  2. “管理 Agent 像管理人”隐喻忽略了 Agent 不会主动 push back 的风险——非技术创始人如何识别 Agent 的系统性盲区
  3. 15+ Agent 并行但缺少测试/验证/Spec 锚定机制说明，长期可维护性如何保障
  4. React Native → Swift 重写“几小时”可能仅指核心骨架，完整功能迁移成本未披露
  5. 非技术创始人成功是否意味着“技术合伙人”角色价值下降，还是仅改变其工作形态
  6. 健康/生物识别数据（HRV、压力信号）的隐私合规处理仍是空白

## [21:00] ingest|摄入《AISE Harness 技术调研报告》（AI 软件工程 Harness 技术发展综述，2026-06）
- 创建 source-summary: `sources/2026-06-09-AISE-Harness-技术调研报告`
- 创建 narrative analysis: `analysis/2026-06-09-AISE-Harness-技术调研报告-叙事解读`
- 更新概念页: Harness-Engineering（新增「四大核心 Agent 循环模式与 Harness 支撑」完整小节：Daemon/ReAct/FSM/Orchestrator 四种模式及 Harness 关键技术实现/模式选择工程判断/业界实践映射；新增「防御性设计：Harness 的三道防线」完整小节：硬计数器/语义收敛与死循环审计/财务与配额熔断；新增「重试范式转移：从追加错误的 Retry 到事务性 Rollback」完整小节：传统后向追加的问题/事务性滚回三步/与角色隔离的互补关系/延迟求解的底层优化三方向）
- 更新 index.md: 添加资料摘要条目、添加 narrative analysis 条目
- 更新 log.md: 追加记录
- **强化**:本文是 Harness-Engineering 概念页从「三支柱/四维度/五特征/验证链路」到「运行时基座底层控制模型」的纵深扩展——将 Harness 从「应该做什么」推进到「四种控制模式下具体怎么做」；四大循环模式为此前分散的 Harness 实践（OpenAI Codex/Cursor Self-Driving/Anthropic 多 Agent Review/黄东旭交叉 Review）提供了统一分类框架
- **互补**:与 `sources/2026-05-05-为什么需要-Harness-Engineering` 形成「为什么需要 Harness → Harness 底层控制模型长什么样」的互补；与 `sources/2026-01-20-当前关于Vibe-Engineering的所有认知都会在1个月内严重过时` 形成「个人多 Agent 协同实践 → 企业级 Harness 基座技术矩阵」的互补；与 `sources/2026-05-06-验证-确保代码忠实于规约` 形成「验证什么 → 验证后如何控制收敛」的互补
- **校准**:将 Harness 从「测试评估床」校准为「智能操作系统内核」；将「重试」从「追加错误信息到上下文」校准为「事务性 Rollback + 擦除负面记忆」；将「多 Agent 并行」从「简单并发」校准为「操作系统级上下文隔离 + MapReduce 结果对齐」
- **矛盾/待观察**:
  1. 报告断言「模型参数规模不再是核心壁垒」，但开源模型与企业级 Harness 成熟度之间是否存在因果倒置——是模型能力足够好才使 Harness 成为可能，还是 Harness 能让差模型变好用？
  2. FSM/DAG 模式的刚性与 Vibe-Engineering「1 个月认知半衰期」的快速迭代需求之间存在张力
  3. 事务性 Rollback 在 LLM 状态（注意力分布）上的完整实现程度——当前是否有运行时真正做到了「清除负面记忆」而不只是「截断上下文」？
  4. `max_iterations <= 10` 的硬计数器在不同任务类型上的最优值差异尚未量化
  5. 报告强调「微服务化局部循环」，但未讨论 Micro-Agent 之间的编排协议标准化问题

## [20:30] config|修改 CLAUDE.md 摄入流程，添加 narrative analysis ⾃动⽣成步骤
- 修改 CLAUDE.md：在摄⼊流程中新增步骤 3，要求每次摄⼊时同时在 wiki/analysis/ 下创建 narrative 分析⻚
- narrative 规范：线性叙事、起转承合、对外分享⼝吻、纯⽂章形态（⽆ YAML/⽆ wiki 链接）、末尾附参考来源
- 创建示例：analysis/2026-04-09-Enterprise-AI-Playbook-叙事解读（展示新流程效果）
- 更新 index.md：添加 narrative analysis 条⽬
- 更新 log.md：追加记录

## [20:00] ingest|摄入《The Enterprise AI Playbook》(Stanford Digital Economy Lab, 2026-04)
- 创建 source-summary: `sources/2026-04-09-The-Enterprise-AI-Playbook`
- 更新概念页: Multi-Model-Orchestration（新增「企业级生产证据」小节：多模型策略成常态/模型抽象层为竞争优势/成本因素动态变化）
- 更新概念页: Model-Commoditization（新增「企业级实证校准」小节：42% 可互换/任务复杂度定义边界/编排层是持久优势/开源进入特定角色/成本因素未来变化）
- 更新概念页: Agent-Control-Plane（新增「企业 Agentic AI 部署证据」小节：成功特征→控制面治理需求映射表/自主行为治理升级）
- 更新概念页: AI-Interaction-Patterns（新增「企业级人机协作模式」小节：升级71%/审批30%/协同22%三模式对比/战略设计选择而非技术限制）
- 更新概念页: Problem-First-AI-Adoption（新增「大企业路径：从问题优先到组织变革」小节：中小企业敏捷模式 vs 大企业制度模式的关键差异）
- 创建实体页: Erik-Brynjolfsson（斯坦福数字经济实验室主任，生产力 J 曲线理论提出者，Workhelix 联合创始人）
- 创建实体页: Stanford-Digital-Economy-Lab（斯坦福数字经济实验室，AI 劳动市场与企业生产力实证研究）
- 更新 index.md: 添加资料摘要条目、新增人物/组织条目
- 更新 log.md: 追加记录
- **强化**:本文是 Multi-Model-Orchestration、Model-Commoditization、Agent-Control-Plane 三个概念页从"理论/产品观察"到"41个组织51个案例跨行业实证"的强化；为 Problem-First-AI-Adoption 补充了大企业制度变革路径，与原有中小企业敏捷路径形成完整光谱
- **互补**:与 [[sources/2026-04-06-马工-别学AI了直接用起来]] 形成「中小企业8周落地 vs 大企业数年制度变革」的互补；与 [[sources/2026-05-02-How-AI-Impacts-Skill-Formation]] 形成「企业制度设计 vs 个人认知协作」的互补；与 [[sources/2026-01-20-当前关于Vibe-Engineering的所有认知都会在1个月内严重过时]] 形成「个体超级生产力 vs 组织级生产力J曲线」的互补
- **校准**:
  - 将"AI落地成败取决于技术"校准为"成败取决于组织能力和流程设计"——技术始终是最容易的部分
  - 将"数据质量是AI前提"校准为"数据访问和集成设计比数据完美更重要"——LLM本身成为数据清洗工具
  - 将"AI必然导致裁员"校准为"减员仅45%，且技术不决定结果，战略选择才决定"——但预警22-25岁早期职业岗位已出现-16%相对就业decline
  - 将"模型选择是关键决策"校准为"42%场景模型可互换，编排层和专有数据才是护城河"
- **矛盾/待观察**:
  1. 报告承认选择偏误（只研究成功案例），MIT NANDA 的95%失败率与本报告51个成功案例之间存在巨大鸿沟，真实成功率可能在两者之间
  2. 当前45%减员率可能代表"地板而非天花板"——随着模型能力提升和经济压力加剧，未来分布可能向减员倾斜
  3. Agentic AI 当前仅20%但增益最高(71%)，随着框架成熟，其对劳动力市场的冲击可能远超当前样本反映的程度
  4. "职能部门是最大阻力源(35%)"的发现与多数组织将AI项目放在技术部门的做法存在结构性矛盾——需要制度层面的治理参与机制
  5. 中国开源模型(Qwen/Kimi/GLM等)在OpenRouter上占据token量前5中的4个，但美国企业部署仍以美国厂商为主——地缘政治因素对模型选择的实际影响尚未量化

## [19:00] compile|创建分析页《AILock-Step vs OpenSpec：验证链路对比》
- 创建 analysis: `analysis/2026-05-06-AILock-Step-vs-OpenSpec-验证链路对比`
- 基于 [[sources/2026-05-06-实践-AILock-Step-的验证链路]] 的 OKR 案例，逐步骤对比两种 SDD 工具在验证链路上的落地差异
- 核心发现：
  - API Contract：AILock-Step 集中式结构化定义 vs OpenSpec 分散在 capability design.md 中（Delta 格式不适合结构化契约）
  - 测试生成：AILock-Step `/generate-tests` 自动生成+显式映射表 vs OpenSpec TDD schema 约束但需手工编写
  - Code Review：AILock-Step 独立 session + spec 一致性报告 vs OpenSpec `/opsx:verify`（expanded workflow）自我验证 + Triple AI skill 补位
  - OpenSpec 验证深度取决于是否启用 expanded workflow（`/opsx:verify` 非默认可用）
- 给出 OpenSpec 下构建同等验证强度的四步操作手册（自定义 schema → Propose 含 Contract → Apply 测试先行 → Verify 四重验证 → Archive 手动同步 design.md）
- 更新 index.md: 添加分析条目
- 更新概念页: Spec-Anchored-Verification / Harness-Engineering / SDD 添加 analysis 引用
- 更新 log.md: 追加记录
- **强化**:本文将 [[analysis/2026-05-05-BMAD-vs-OpenSpec-vs-Spec-Kit-SDD三条路径]] 的「工具特性对比」推进到「同一验证链路的不同落地方式」——从"它们有什么不一样"深化为"做同一件事每一步分别怎么做"
- **互补**:与 [[sources/2026-05-06-实践-AILock-Step-的验证链路]] 形成「原生实现 vs 跨工具映射」互补——前者展示 AILock-Step 的完整链路，后者展示该链路在 OpenSpec 约束下的等价变形
- **校准**:OpenSpec 的 `/opsx:verify` 属于 expanded workflow 非默认可用；design.md 不在 OpenSpec 的 delta 合并机制内，Archive 后需手动同步基线——这两点纠正了此前"OpenSpec 验证开箱即用"的过度简化
- **矛盾/待观察**:1. OpenSpec design.md 的手动同步机制在频繁迭代下的遗忘风险；2. 50KB 硬限下复杂接口 contract 的容量边界；3. Triple AI Validation skill 与 OpenSpec 核心工作流的集成紧密度

## [18:30] ingest|摄入《实践：AILock-Step 的验证链路》
- 创建 source-summary: `sources/2026-05-06-实践-AILock-Step-的验证链路`
- 更新概念页: Spec-Anchored-Verification（新增「验证链路的完整闭环实践」完整小节：API Contract 定义边界/双重来源测试生成/显式映射表可追溯性/独立 Review Agent 输出 spec 一致性报告/两份报告审查界面/从好的工程实践到生存前提的跃迁）
- 更新概念页: Harness-Engineering（新增「验证链路的 AILock-Step 实践」小节：三步验证链路的完整执行演示/单 Agent vs 多 Agent 场景的差异定位）
- 更新概念页: SDD（新增「Spec→Contract→测试→Review：执行层的完整闭环」小节：验证链路在执行层的落地流程图/SDD 提供上游锚点、Harness 提供下游执行机制的分工）
- 更新 index.md: 添加资料摘要条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Spec-Anchored-Verification]] 从「理论框架 + 分维度方法」到「完整落地链路」的最终整合——将测试验证行为正确性、review 验证语义完整性、contract 定义模块边界三条线拧成一根绳；是 [[Harness-Engineering]] 卷一「1→10x」阶段闭环原则的完整执行演示
- **互补**:与 [[sources/2026-05-06-验证-确保代码忠实于规约]]（为什么）、[[sources/2026-05-06-测试基建前置-把规约变成可执行约束]]（测试怎么做）、[[sources/2026-05-06-Code-Review-补位测试覆盖不到的意图漂移]]（review 怎么做）形成「理论→分维度方法→整合实践」的完整四部曲
- **校准**:将「验证」从「编码后的质量检查步骤」重新定位为「贯穿 spec→contract→测试→review→合并全流程的工程基建」——验证不是某个阶段的附加动作，是单任务闭环的结构性组成部分
- **矛盾/待观察**:1. 显式映射表在规则数量增长到数百条时的维护成本；2. Scope check 中「被动重构导致 out-of-scope 变更」的判定标准精细度；3. 多 Agent 并行场景下 contract 版本权威的维护机制

## [18:00] re-ingest|重新摄入《验证：确保代码忠实于规约》（补全缺失内容）
- 更新 source-summary: `sources/2026-05-06-验证-确保代码忠实于规约`，status 从 draft 改为 reviewed
- 补全内容：
  - 开篇 OKR 案例：13 条 AC + 5 条 BR、12+4 文件、26/28 PASS
  - BR-002 完整详情：前端有 Element UI 提示、后端缺 ServiceException 校验、绕过 API 即可突破
  - BR-004 完整详情：默认选中当前季度逻辑缺失
  - "代码质量 vs 意图偏离"对比表：null check/命名等 AI 自己能发现 vs 意图偏离真正难检测
  - 各框架盲区详细展开：BMAD 三层信息不对称审查、Spec Kit Constitution+10 类歧义检测、OpenAI/Anthropic 多 Agent eval
  - "脱离 spec 的 review 只会产出'代码结构清晰建议补充异常处理'这类正确但无用的反馈"
  - TDAD 论文三组对比：6.08% 基线 / 9.94% 流程指令（升高） / 1.82% 具体指令（降低 70%）
  - 三个结构性要求：加入"第十步偏离第一步 spec"、"review Agent 同时处理 2000 行+spec 超出范围"等关键论据
  - 章节预告：测试基建 → Code Review → AILock-Step 完整链路
  - 待观察问题新增：BR-002 与 BR-004 的检测难度差异（测试可发现 vs review 才能发现）
- 更新概念页: Spec-Anchored-Verification
  - 新增"锚点案例"小节：完整展开 BR-002/BR-004 作为贯穿全书的意图偏离标杆案例
  - 新增"代码质量问题 vs 意图偏离"对比表
  - 新增"脱离 spec 的 review 只产生无用反馈"论点
  - 新增各框架/工具共同盲区分析表（BMAD/Spec Kit/OpenAI/Anthropic/TDD/lint/单元测试）
  - 重构"三个结构性要求"：明确两特征决定（漂移+容量）、加入"容量限制也适用于 review"、补充 DORA 2025 放大器论述
  - 修正 TDAD 表格：补充 6.08% 基线对照位，标注流程指令"升高 64%"这一反常发现
- **校准**：此前的 source-summary 遗漏了 BR-002/BR-004 的完整细节，导致意图偏离概念缺乏具象锚点；source-summary 的"实操方向"过于笼统，未点明"测试验证行为正确性、review 验证语义完整性"的互补定位
- **矛盾/待观察**：流程指令升高 64% 的原因原文未深入分析——一种可能是流程指令引入了人类高估 TDD 完备性的系统性偏差，需要后续文献验证

## [17:45] ingest|摄入《Code Review：补位测试覆盖不到的意图漂移》
- 创建 source-summary: `sources/2026-05-06-Code-Review-补位测试覆盖不到的意图漂移`
- 更新概念页: Spec-Anchored-Verification（新增「Code Review 的具体操作方法」完整小节：review 三个核心问题/spec 一致性报告格式/独立 session 原则/交叉模型审查/规模化数据）
- 更新概念页: Harness-Engineering（在「验证：确保代码忠实于规约」下新增「Code Review 作为 spec 一致性检查」小节：三个问题/产出格式/独立 session/交叉模型/Anthropic+OpenAI 数据）
- 更新概念页: Poor-Self-Evaluation-Bias（扩展「解决方案」：独立 session+交叉模型+Anthropic 量化数据；扩展「与 Harness 的关系」：review 的 spec 锚定三个标准）
- 更新 index.md: 添加资料摘要条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Spec-Anchored-Verification]] 从"测试维度"到"review 维度"的完整展开——上篇论证测试+review 缺一不可，本篇论证 review 怎么做、标准是什么、为什么必须独立 session；将 [[Poor-Self-Evaluation-Bias]] 的"角色隔离"原则推进到工程数据层面
- **互补**:与 [[sources/2026-05-06-测试基建前置-把规约变成可执行约束]] 形成「测试（行为验证）+ review（语义验证）」的互补对——两者共同构成 spec 锚定验证的完整闭环
- **校准**:将 code review 从「代码质量检查」重新定位为「spec 一致性检查」——review 的参照系不是代码，是规约；产出不是建议清单，是 spec 一致性报告
- **矛盾/待观察**:1. 多个 review agent 并行审查的分类标准（逻辑/API/权限/规范）与 spec 一致性标准之间的关系——是叠加还是合并？2. Anthropic「7.5 个问题/PR」中「实质性发现」的定义是否包含 spec 偏离还是仅限传统 bug 类问题

## [17:15] ingest|摄入《测试基建前置：把规约变成可执行约束》
- 创建 source-summary: `sources/2026-05-06-测试基建前置-把规约变成可执行约束`
- 更新概念页: Spec-Anchored-Verification（新增「测试基建前置：从规约到可执行约束」完整小节：翻译时序/API Contract 边界/测试双重来源/集成测试优先/Mock 纪律/偏差压缩/测试作为规约质量早期检验）
- 更新概念页: Harness-Engineering（在「验证」小节下新增「测试基建前置的具体方法」：测试双重来源/Mock 纪律/集成测试优先/偏差压缩执行节奏）
- 更新概念页: SDD（新增「Spec→测试：可执行化的翻译层」小节：三维模型对应两重测试来源/测试对规约质量的早期检验；新增「API Contract：模块边界与测试粒度」小节）
- 更新 index.md: 添加资料摘要条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Spec-Anchored-Verification]] 从「为什么」到「怎么做」的完整展开，将 spec 锚定验证落地为「spec→测试翻译+API contract 边界+集成测试为主+过程持续运行」的实操方法；是 [[Harness-Engineering]] 「闭环」原则在执行层的完整落地
- **互补**:与 [[sources/2026-05-06-验证-确保代码忠实于规约]] 形成「理论框架→实操方法」互补——上篇论证为什么测试+review 缺一不可，本篇论证测试基建怎么在前置阶段搭建
- **校准**:将「测试」从「编码后的质量检查」重新定位为「spec 的可执行形式」——测试不是附加品，是 spec 意图的翻译层；将「集成测试 vs 单元测试」从「偏好之争」校准为「验收 vs 辅助」的功能分工
- **矛盾/待观察**:1. 验收标准测试与 API contract 测试的重复/边界问题——同一接口行为被两种来源同时覆盖时的维护成本；2. 前端 mock server 基于 contract，但 contract 本身在迭代中变化时的同步成本；3. 多 Agent 并行开发下 contract 的版本管理（谁来维护 contract 的权威版本）

## [16:45] ingest|摄入《验证：确保代码忠实于规约》
- 创建 source-summary: `sources/2026-05-06-验证-确保代码忠实于规约`
- 创建概念页: Spec-Anchored-Verification（以规约为锚点的验证：spec 作为验证 single source of truth，测试+code review 互补缺一不可）
- 更新概念页: Harness-Engineering（新增「验证：确保代码忠实于规约」完整小节：验证锚点是规约/三个结构性要求/测试+review 互补）
- 更新概念页: Intent-Alignment（新增「验证层：运行时端的意图对齐」小节：传递→验证→纠偏闭环，翻译漂移/注意力漂移/意图偏离三类运行时偏差）
- 更新概念页: SDD（更新「未解决的缺口」和「与 Harness 的关系」：明确 Spec-Anchored-Verification 填补运行时验证缺口）
- 更新概念页: Vibe-Coding（新增「执行层的隐性失败：意图偏离」小节：代码没问题但功能偏离 spec，现有工具盲区）
- 更新概念页: Poor-Self-Evaluation-Bias（新增「为什么角色隔离仍不足够」小节：独立 review Agent 不看 spec 仍检测不了意图偏离；更新 Harness 缓解机制加入 spec 锚定）
- 更新 index.md: 添加资料摘要条目、概念条目、更新 Harness-Engineering 描述
- 更新 log.md: 追加记录
- **强化**:本文是 [[Harness-Engineering]]「闭环」原则在验证层的完整展开，TDAD 论文数据（1.82% 回归率）为 Harness 有效性提供量化证据；将 [[Intent-Alignment]] 从「文档端一致性」延伸到「运行时验证层」，形成传递→验证的完整闭环
- **互补**:与 [[SDD]] 形成「上游规约→下游验证」互补——SDD 定义「对是什么」，本文定义「怎么确认 Agent 真的做了」
- **校准**:将「测试」和「code review」从独立工程活动重新定位为同一目标（spec 一致性）的两个互补手段；将 Harness 验证焦点从「代码质量」校准为「spec 忠实度」
- **矛盾/待观察**:1. TDAD 论文中 spec→测试映射的自动化实现程度未完全明确；2. 验证前置基建的成本收益比在不同规模项目中的边界条件；3. AILock-Step 框架中测试基建与 code review 的具体协同机制待后续章节摄入后补充

## [23:50] compile|创建综合分析页《BMAD vs OpenSpec vs Spec Kit：SDD 三条路径》
- 创建 analysis: `analysis/2026-05-05-BMAD-vs-OpenSpec-vs-Spec-Kit-SDD三条路径`
- 基于 BMAD METHOD、OpenSpec、GitHub Spec Kit 官方仓库及社区资料的调研
- 梳理三者在核心定位、Context 控制策略、工作流复杂度、Agent 角色设计、Spec 格式、适用场景六个维度的差异
- 关键发现：
  - BMAD = Agent-as-Code 工作流系统，四层 Context 防御（Single Step Per Context + JIT Loading + Tiered Knowledge + Subagent Isolation）
  - OpenSpec = CLI-driven 框架，50KB 硬限 + Delta specs + 两文件夹隔离
  - Spec Kit = Prompt-driven 工具包，18.6k command tax + 完整规格 + 无框架级限制
- 与知识库概念的三重映射：Intent-Alignment（多角色传递 vs Delta 精确性 vs 交叉验证）、Harness-Engineering（最完整 vs 最刚性 vs 最弱）、SDD（最重 vs 最轻 vs 中等）
- 更新 index.md: 添加分析条目
- 更新 log.md: 追加记录
- **强化**:本文将 Intent-Alignment「信息架构」、Harness-Engineering「上下文工程」、SDD「规格驱动」三个概念页从理论层落地到具体工具的评估框架
- **互补**:三个工具形成「工厂(BMAD) vs Git(OpenSpec) vs 宪法(Spec Kit)」的互补图景——没有绝对优劣，只有与问题匹配度的差异
- **校准**:知识库此前将四个框架（OpenSpec/AILock-Step/BMAD/Spec Kit）并列描述为「做了几乎相同的 context 限制决策」——本文校准为：四者在「限制 context」这一目标上一致，但实现策略差异极大（硬限/隔离/增量/无限制）
- **矛盾/待观察**:1. BMAD 的频繁会话切换对开发者体验的摩擦成本尚未量化；2. OpenSpec 的 50KB 上限在超大型项目（微服务/多模块）下的可扩展性；3. Spec Kit 的 subagent delegation 提案是否能从根本上解决 context tax

## [23:45] compile|创建分析页《Spec Kit 实际操作与加载控制分析》
- 创建 analysis: `analysis/2026-05-05-Spec-Kit-实际操作与加载控制分析`
- 基于 GitHub Spec Kit 官方仓库、Issue #1401（18.6k context tax）、Discussion #912（subagent delegation）的调研
- 梳理 Spec Kit 八命令 gated 工作流与加载控制的三层机制：命令文件自动加载 → 工作流动态加载 → Git 分支隔离
- 对比社区两种解决方案：手动开关（disable/enable）vs subagent delegation（结构性方案）
- 与知识库概念的三重映射：Intent-Alignment（意图外部化/结构消除歧义/交叉验证）、Harness-Engineering（闭环原则/多 Agent 隔离/五个结构性特征印证）、SDD（理论→可执行命令的映射，缺少框架级硬性限制）
- 更新 index.md: 添加分析条目
- 更新 log.md: 追加记录
- **强化**:本文将 Intent-Alignment「信息架构」和 Harness-Engineering「上下文工程」从理论层落地到具体工具的评估框架，为选择/改造 SDD 工具提供判断标准
- **互补**:Spec Kit 在操作层补充了知识库缺失的「具体工具映射」，知识库中的理论层为评估 Spec Kit 优劣提供标准——两者形成「理论↔实践」互补
- **校准**:Spec Kit 并非如 OpenSpec/AILock-Step 般在框架层强制限制 context，而是依赖 Agent 客户端的自动加载 + Prompt 内文件引用——这一实现方式比知识库中「社区框架一致决策」的描述更弱
- **矛盾/待观察**:1. 工具税悖论——消除歧义的工具本身消耗 93% 的 context window；2. subagent delegation 的人机介入点、状态同步、成本边界尚未明确
格式: `## [HH:MM] <操作>|<描述>`
操作类型:scaffold, ingest, query, compile, lint, audit, promote

## [23:30] ingest|摄入《用结构传达意图：分层与维度》
- 创建 source-summary: `sources/2026-05-05-用结构传达意图-分层与维度`
- 更新概念页: Intent-Alignment(新增「信息分层的理论框架」完整小节：四层信息/判断指标/加载策略/上下沉信号；新增「结构化描述的三维模型」小节：意图/验收/约束 + 空字段代价；新增「用结构消除歧义」小节)
- 更新概念页: SDD(新增「Spec 结构的三维模型」小节：主流框架字段差异背后的统一三维度 + 空字段代价；新增「分解过程中的漂移」小节：翻译漂移/注意力漂移/逐层叠加)
- 更新概念页: Harness-Engineering(新增「信息分层的理论依据」小节：四层信息的内在性质与 Ryan 三文档体系的同构关系)
- 更新 index.md: 添加资料摘要条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Intent-Alignment]]「信息架构」视角的完整展开——从信息内在性质推导出分层必要性，将「加载什么」深化为「为什么这样加载」；是 [[SDD]] spec 结构的元理论，将 BMAD/OpenSpec/Spec Kit/AILock-Step 的字段差异统一为三个底层维度
- **互补**:与 [[Harness-Engineering]]「规约迭代循环」形成「理论框架 ↔ 具体实现」互补——本文证明信息分层是信息内在性质的必然结果，Ryan 的实践是该原则的工程映射
- **校准**:将「消除歧义」从「写更多自然语言」校准为「回答关键维度的结构化问题」；将「交叉验证」从抽象原则具体化为「不同角度检查层级间一致性」的核心机制
- **矛盾/待观察**:与 [[sources/2026-05-05-迭代出一份可执行的规约]] 同一未解决点——按用户价值拆分的子 feature 间存在数据模型/接口依赖时的迭代顺序问题

## [23:00] ingest|摄入《迭代出一份可执行的规约》
- 创建 source-summary: `sources/2026-05-05-迭代出一份可执行的规约`
- 更新概念页: Harness-Engineering(新增「规约迭代循环」完整小节：六阶段迭代流程/交叉验证机制/按用户价值拆分/迭代深度匹配返工代价/意图对齐分工)
- 更新概念页: SDD(新增「Spec 迭代循环」小节：交叉验证的三次独立理解/收敛标准/何时拆分)
- 更新概念页: Intent-Alignment(新增「意图对齐的两层检查」小节：结构性一致性 vs 语义正确性/Agent 与人的分工边界)
- 更新 index.md: 添加资料摘要条目
- 更新 log.md: 追加记录
- **强化**:本文是 [[Harness-Engineering]]「闭环」原则在 spec 层的具体操作方法论，将原则落地为可执行的六阶段循环；是 [[SDD]] 从「是什么」到「怎么做」的操作层补充
- **互补**:与 [[Intent-Alignment]] 形成「结构一致性 vs 语义正确性」的互补——交叉验证解决前者，人的意图 review 解决后者
- **校准**:将 SDD「文档链逐层约束」具体化为「spec → task list → checklist」三轮交叉验证，每轮都是 Agent 对需求的重新理解
- **矛盾/待观察**:文中假设按用户价值拆分的子 feature 可独立收敛，但未讨论子 feature 间存在数据模型/接口依赖时的迭代顺序问题

## [22:00] ingest|摄入《引言：为什么需要 Harness Engineering》
- 创建 source-summary: `sources/2026-05-05-为什么需要-Harness-Engineering`
- 更新概念页: Harness-Engineering(新增"Agent 五个结构性特征"完整小节：有限处理容量/忠实执行/无记忆积累/无后果感知/高吞吐零边际成本，每个特征含具体场景与 Harness 应对策略)
- 更新概念页: Vibe-Coding(新增"崩溃模式与技术债自强化循环"小节：honeymoon 幻觉→崩溃拐点→坏模式自复制放大)
- 更新 index.md: 添加资料摘要条目
- 更新 log.md: 追加记录
- **强化**:本文是前言中"Agent 五个结构性特征"的逐特征详细展开，将清单深化为可操作的设计输入；技术债自强化循环补充了 Vibe-Coding 概念页的动态退化分析
- **校准**:将"有限处理容量"具体化为"标称容量 vs 有效容量"(attention 机制导致)，区分大任务(空间超载)和长链推理(时间超载)两个独立场景
- **待观察**:五个特征基于 Transformer 架构的内在属性，判断"不会随模型能力增长消失"，对未来非 Transformer 架构(如状态空间模型)是否仍成立需持续观察

## [21:30] ingest|摄入《意图对齐：Vibe Coding 为什么失败》
- 创建 source-summary: `sources/2026-05-05-意图对齐-Vibe-Coding-为什么失败`
- 创建概念页: Intent-Alignment(意图对齐：有限context与不均匀注意力下的意图传递工程问题)
- 更新概念页: Vibe-Coding(新增"对话模式的三种失败"小节：注意力衰减/指令冲突/compaction丢失；新增"Context限制下的信息架构"小节：AnyClaw案例/社区框架一致决策)
- 更新 index.md: 添加资料摘要/概念条目
- 更新 log.md: 追加记录
- **强化**:本文将 Vibe Coding 的"不可靠"从笼统感受具体化为三种可诊断的失败模式，并追溯到"意图活在对话里"这一结构性根源
- **互补**:"信息架构"视角补充了 Harness-Engineering "上下文工程"支柱——不仅知道"加载什么"，更要知道"不加载什么"和"如何组织加载顺序"
- **校准**:Vibe Coding 的失败不仅是"没有验证"（开环控制），更是"意图传递机制本身的结构性缺陷"——即使有人工验证，意图偏差已经产生
- **矛盾/待观察**:本文预告后续章节将展开"信息分层和结构化维度的方法论框架"及"可交给Agent执行的spec"，具体内容待摄入

## [21:00] ingest|摄入《Harness Engineering 手册：百倍生产力的可靠软件交付（前言）》
- 创建 source-summary: `sources/2026-05-05-Harness-Engineering-手册前言`
- 创建实体页: 冯若航(Pigsty创始人,一人用AI维护460+扩展的PostgreSQL发行版,日常调度十个Agent并行), Pigsty(企业级PostgreSQL发行版,AI原生维护标杆), 马驰(AgentsZone核心成员,《Harness Engineering手册》编者)
- 更新实体页: 付权智(新增本书编者身份、关联马驰), AgentsZone(新增本书集体创作输出), 黄东旭(新增本书100x标杆案例引用,与冯若航并列)
- 更新概念页: Harness-Engineering(新增"两个基本原则"小节:闭环/演进;新增"三卷生产力阶梯"小节:1→10→100x+组织治理;更新关联实体), Vibe-Coding(新增"开环控制的本质问题"小节,与Harness闭环原则形成对照)
- 更新 index.md: 添加资料摘要/人物/社区/产品条目
- 更新 log.md: 追加记录
- **强化**:本书是 Harness-Engineering 的系统化、手册级展开，将此前分散观察整合为完整理论框架+可操作实践方法论
- **互补**:与 Vibe-Engineering 形成"个体实践→系统方法"互补——黄东旭文章是个人经验极限探索，本书提炼可复制部分为制度
- **校准**:Harness Engineering 定位为"崭新完整的软件工程制度"而非原有制度补丁；执行者变了制度必须跟着变
- **矛盾/待观察**:1.5x→100x跃升是否对所有软件项目类型都成立（前端/后端/infra/算法），前言未给出不同领域边界条件
- 创建 source-summary: `sources/2026-01-26-从过程确定性到结果确定性`
- 创建概念页: Result-Certainty(结果确定性哲学：过程确定性vs结果确定性的对比、经济学差异、实现机制、边界条件)
- 更新实体页: 鸭哥(新增文章列表、核心观点：结果确定性/Claude Code作为Agentic Runtime/Evaluation-First契约层)
- 更新实体页: Claude-Code(新增"可复用 Agentic Runtime"视角：生态级基础设施、运行时层外包、契约层留白)
- 更新概念页: Agent-Self-Drive(新增"运行时层与契约层的互补关系"小节、翻译任务实战验证案例)
- 更新概念页: Harness-Engineering(新增"四层结构视角"与"契约层的验收标准设计"小节)
- 更新 index.md: 添加资料摘要/概念条目
- 更新 log.md: 追加记录
- **强化**:本文是 Agent-Self-Drive 在"翻译场景"的完整实战展开，将反馈循环从抽象原则落地为文件系统持久化+自验证脚本；是 Harness-Engineering 四层结构视角的原创性补充
- **校准**:Claude-Code 的产品定位从"编程助手"提升到"生态级 Agentic Runtime"，模型提供商主动适配等于帮所有开发者填坑
- **互补**:"结果确定性"构成 Vibe-Coding 与 SDD 之间的哲学桥梁——Vibe-Coding 放弃过程控制，SDD 收紧输入端，本文在输出端用验收标准收窄不确定性，三者形成完整的"输入-过程-输出"控制体系
- **矛盾/待观察**:结果确定性的经济学假设(intelligence越来越便宜)与当前API成本在长尾任务上的兼容性；sandbox安全方案的标准化程度

## [17:00] ingest|摄入《当前关于 Vibe Engineering 的所有认知都会在 1 个月内严重过时》(黄东旭)
- 创建 source-summary: `sources/2026-01-20-当前关于Vibe-Engineering的所有认知都会在1个月内严重过时`
- 创建概念页: Vibe-Engineering(AI原生研发更高维度范式：组织形态/人机分工/认知迭代/系统进化；1个月认知半衰期、5万行阈值、90%验收瓶颈、头狼+狼群)
- 更新实体页: 黄东旭(新增模型偏好GPT-5.2/Opus4.5/Gemini3Pro、ralph-loop技巧、多Agent协同工作流、Rust首选、90%验收时间展开)
- 更新概念页: Vibe-Coding(新增"从 Vibe Coding 到 Vibe Engineering"对比表，演进路径加入 Vibe-Engineering 节点)
- 更新概念页: Harness-Engineering(新增"多Agent协同：Harness的角色隔离实践"小节：交叉Review工作流/并行开发/ralph-loop技巧；新增"复杂度阈值与模块治理"小节：5万行阈值与linter机械执行；新增"个人工作流中的知识固化"小节：work.md/todo.md/agents.md/.codex/knowledge 三层映射)
- 更新 index.md: 添加资料摘要/概念条目
- **强化**:本文是黄东旭"头狼+狼群"模式的完整展开，将此前零散观察(5万行/90%验收/1+1<2)系统化为人机分工五阶段、多Agent协同工作流、模型选择指南
- **互补**:Vibe-Engineering 与 Vibe-Coding 形成维度互补——前者回答"组织如何设计"，后者回答"代码如何生成"；与 PTO 框架构成两极(精英路线vs可复制路线)
- **校准**:Harness-Engineering 此前侧重"系统级"基础设施，本文补充了"个人工作流级"最小实践(work.md/agents.md/todo.md)和"多Agent交叉Review"运行时机制
- **矛盾/待观察**:头狼"1+1<2"与PTO"三人协作超越超级个体"的边界条件(项目规模/模块耦合度/AI水平)尚未明确；AI-Native组织"难自底向上生长"的预言与渐进转型路径的兼容性待验证

## [16:00] ingest|摄入《学习PingCAP，打造你公司的AI原生软件开发团队》(AgentsZone)
- 创建 source-summary: `sources/2026-05-03-学习PingCAP打造AI原生软件开发团队`
- 创建实体页: 黄东旭(PingCAP CTO,头狼+狼群模式提出者,5万行阈值/90%验收瓶颈), PingCAP(平凯星辰,TiDB,AI原生开发实验场)
- 创建概念页: Product-Tri-Ownership(PTO框架,PO/QO/TO三人组+AI Agent,一天一个用户故事目标)
- 更新实体页: 付权智(添加PTO框架观点与本文来源), AgentsZone(添加方法论输出表格与PTO框架), Claude-Code(添加10天10版本发布节奏参考)
- 更新概念页: Vibe-Coding(新增"遗留问题的团队级回应"小节,头狼模式vs PTO框架作为两条规模化路径)
- 更新 index.md: 添加资料摘要/人物/公司/概念条目
- **强化**:本文是 Vibe-Coding 在"团队规模化"维度的系统回应,填补了"从个体精英到普通团队"的路径空白;QO的独立验证原则与 Harness-Engineering "外部约束贡献80%可靠性"完全同构
- **互补**:头狼模式与PTO框架构成两极——精英路线vs可复制路线;"培训模式"为无法组织变革的团队提供渐进路径,与 Problem-First-AI-Adoption 的"最小可用切入"精神一致
- **校准**:黄东旭90%验收时间瓶颈证明仅靠TO个人扛质量不可持续;独立QO将质量工作从"最后验收"前移到SDLC全流程
- **矛盾/待观察**:头狼"1+1<2"与PTO"三人协作可超越超级个体"的判断边界条件(项目规模/团队成熟度/AI能力水平)尚未明确

## [15:30] compile|综合 SDD 与 Harness 概念页，创建 PRD 后执行步骤分析页
- 创建 analysis: `analysis/2026-05-03-PRD之后SDD与Harness执行步骤`
- 将 SDD 三层层级 + Harness 四维度实践整合为可执行 checklist（SDD 阶段 / Harness 阶段 / 反馈闭环）
- 提炼关键数字：AGENTS.md ~100 行、Harness 80% 可靠性贡献、步骤拆分阈值 <8~10
- 更新 index.md: 添加分析条目
- 与已有内容关系：**强化**:本文是 [[concepts/SDD]] 和 [[concepts/Harness-Engineering]] 在操作层的 checklist 化;**互补**:将 OpenAI 四维度实践按搭建顺序重组（上下文→可观测性→架构约束→熵管理），而非原文章的并列呈现;**校准**:明确 PRD 在 SDD 文档链中的定位（需求规格层级），消除"PRD 和 SDD 是什么关系"的模糊地带

## [12:45] update|更新分析页《PRD之后SDD与Harness执行步骤》
- 新增"翻译层"章节：PRD → AI可执行规格（acceptance-criteria.md + self-verify.py + context/）
- 新增"上中下三策"小节：信息形态决定AI上限，AI-first顺序逆转传统human-first
- 新增"个人工作流三要素"小节：反馈闭环/上下文供给/资产积累与OpenAI四维度形成互补映射
- 新增"Mono Repo文件结构配置"：推荐目录结构 + 关键文件说明
- 新增"45分钟算法改进闭环"实战验证：展示轻量级SDD（上下文即规格）+ Harness自主执行
- 更新执行Checklist：加入翻译层、资产积累、无基础设施时的最小Harness
- 更新关键数字：加入开环vs闭环5~10倍差距、2分钟→45分钟杠杆比
- 更新与已有概念关系：补充AI-Interaction-Patterns校准、Problem-First-AI-Adoption补充
- 更新 index.md: 更新analysis条目描述

## [12:15] ingest|摄入《用好AI的第一步：停止和AI聊天》(grapeot/鸭哥)
- 创建 source-summary: `sources/2026-05-02-用好AI的第一步：停止和AI聊天`
- 更新实体页: 鸭哥(新增文章列表与核心观点：10倍差距/AI-first/资产飞轮)
- 更新实体页: Cursor(新增"不仅是编程工具"与"资产积累飞轮"视角，补充 Mono Repo 上下文聚合)
- 更新概念页: Harness-Engineering(新增"个人工作流三要素"小节，将反馈闭环/上下文供给/资产积累映射到三支柱)
- 更新概念页: AI-Interaction-Patterns(新增"开环 vs 闭环"小节，校准 Iterative Debug 在闭环工具下的质变)
- 更新概念页: Agent-Self-Drive(新增"45分钟算法改进闭环"案例，展示非确定性任务中的自驱威力)
- 更新 index.md: 添加资料摘要条目
- 未发现与既有内容的强矛盾;**强化**:本文是 Harness-Engineering 和 Agent-Self-Drive 在"个人工作流"维度的系统级阐述，45分钟案例完美诠释自驱三位一体;**互补**:"上中下三策"补充了 Problem-First-AI-Adoption 的落地路径——信息形态决定AI上限;**校准**:AI-Interaction-Patterns 中 Iterative Debug 的有效边界取决于工具形态（开环vs闭环），而非模式本身

## [11:45] compile|综合《以一个简单任务为例看AI落地的关键决策》与《有目标才能有手段-AI-Agent-自驱的两个核心原则》，创建分析页
- 创建 analysis: `analysis/2026-05-02-实践用好AI的路径-从五个决策到两个原则`
- 提炼五层落地路径：选对环境→定义成功→结果导向→分治约束→反馈闭环
- 更新 index.md: 添加分析条目

## [11:30] ingest|摄入《以一个简单任务为例看AI落地的关键决策》(grapeot/鸭哥)
- 创建 source-summary: `sources/2026-05-02-以一个简单任务为例看AI落地的关键决策`
- 创建实体页: 鸭哥(grapeot，独立技术写作者，聚焦 Harness 工程与 Agentic AI 实战)
- 更新概念页: Agent-Self-Drive(新增"实战验证：300篇文章加SEO Summary"小节，展示2分钟→45分钟杠杆比)
- 更新概念页: Harness-Engineering(新增"从系统级到Prompt级的Harness最小实践"小节，证明无CI时Prompt层反馈循环同样有效)
- 更新 index.md: 添加资料摘要/人物条目
- 未发现与既有内容的强矛盾;**强化**:本文是Agent-Self-Drive和Harness-Engineering的实战验证，"先写测试再干活"是原则一（先定义成功）的具体落地;**互补**:本文"divide and conquer"策略补充了Agent-Self-Drive中"步骤超过8~10个考虑拆分"的边界判断标准——context window饱和是核心信号;**校准**:Harness-Engineering此前侧重系统级机制，本文证明Prompt级确定性判定可在无基础设施时独立生效

## [10:58] ingest|摄入《有目标才能有手段：让 AI Agent 自驱的两个核心原则》(Wang Huan)
- 创建 source-summary: `sources/2026-05-02-有目标才能有手段-AI-Agent-自驱的两个核心原则`
- 创建实体页: Wang-Huan(独立技术写作者,聚焦 Agent 自驱闭环与 Skill Prompt 设计)
- 创建概念页: Agent-Self-Drive(先定义成功+结果导向+反馈循环的三位一体方法论)
- 更新概念页: Harness-Engineering(新增"Prompt 层自驱闭环"小节，补充验收标准/自验证脚本/结果导向执行在 Harness 中的定位)
- 更新 index.md: 添加资料摘要/人物/概念条目
- 未发现与既有内容的强矛盾;**强化**:本文是 Harness-Engineering 在 Prompt 层的具体展开，"反馈循环"从系统级 CI/linter 下沉到单次 Skill 执行;**互补**:与 Goal-Context-Constraints 三元组形成操作层映射，"目标"对应验收标准、"约束"对应 MUST/SHOULD/MAY 三级区分;**校准**:Harness-Engineering 此前侧重系统级机制，本文证明 Prompt 级确定性判定同等关键

## [10:48] ingest|摄入《SDD之外是Harness吗》(付权智, AgentsZone)
- 创建 source-summary: `sources/2026-05-02-SDD之外是Harness吗`
- 创建实体页: 付权智(AgentsZone 核心成员, Harness/SDD 方法论倡导者), Ryan-Lopopolo(OpenAI 工程师, Codex Harness 博文作者)
- 创建概念页: SDD(规格驱动开发), Vibe-Coding(AI 自主写代码范式), Poor-Self-Evaluation-Bias(同一 LLM 写审代码的自欺欺人偏差)
- 更新概念页: Harness-Engineering(新增 OpenAI 四维度实践、不确定性窗口理论、业界证据/LangChain/Anthropic/Vercel、与 SDD 关系)
- 更新 index.md: 添加资料摘要/人物/概念条目
- 未发现与既有内容的强矛盾;**强化**:本文是 Harness-Engineering 三支柱模型的具体工程展开，OpenAI 四维度实践可映射到三支柱并大幅细化;**校准**:此前"知识是目的"视角需补充运行时机制（可观测性/反馈循环）与知识分层同等关键

## [09:38] ingest|摄入《别学AI了，直接用起来》(马工，Agent特区论坛)
- 创建 source-summary: `sources/2026-04-06-马工-别学AI了直接用起来`
- 创建实体页: 马工(Agent特区论坛发起人), AgentsZone(社区)
- 创建概念页: Problem-First-AI-Adoption(问题优先的AI落地策略), North-Star-Metric(北极星指标), Knowledge-Half-Life(知识半衰期)
- 更新概念页: Cognitive-Offloading(新增与"集邮癖"的对比表), Skill-Formation(新增"学习策略双重约束"与知识半衰期关联), Harness-Engineering(相关链接更新)
- 更新 index.md: 添加新条目(资料摘要/人物/社区/概念)
- 未发现与既有内容的强矛盾;**互补**:本文"问题优先落地"视角与论文《How AI Impacts Skill Formation》"个人认知协作"视角构成镜像

## [20:28] ingest|摄入《Anthropic 让 Claude Cowork 跑别家模型，这件事比看上去更反常》
- 创建 source-summary: `sources/2026-04-27-Claude-Cowork-第三方模型与Agent基础设施护城河`
- 创建实体页: Anthropic, Claude-Cowork, Claude-Code, OpenAI, AWS, Google, Microsoft, Cursor
- 创建概念页: MCP, Agent-Control-Plane, Multi-Model-Orchestration, Client-Stickiness, Model-Commoditization
- 更新 index.md 添加新条目
- 未发现与既有内容的矛盾

## [20:35] ingest|摄入《Harness不是目的，知识才是护城河 —— 一个AI工程交付团队的知识沉淀实践》
- 创建 source-summary: `sources/2026-04-27-Harness不是目的知识才是护城河`
- 创建实体页: 腾讯, stevenpxiao
- 创建概念页: Harness-Engineering（此前 index 引用但文件缺失，现补齐）
- 更新实体页: Anthropic（新增 Claude Code Harness 特征）, Claude-Code（新增长时运行稳定性/情绪论文）, Cursor（新增 Self-Driving 多 Agent 协同视角）, OpenAI（新增 Codex 人机交互协议视角）
- 更新 index.md 添加新条目
- 未发现与既有内容的矛盾

## [20:00] re-ingest|重新审阅论文《How AI Impacts Skill Formation》并补充遗漏发现
- 更新 source-summary: `sources/2026-05-02-How-AI-Impacts-Skill-Formation`
  - 补充发现 4「粘贴 vs 手抄:时间投入 ≠ 认知投入」：直接粘贴(n=9)与手动输入 AI 代码(n=9)的笔试成绩无显著差异，认知 effort 比 raw time 更重要
  - 补充发现 5「完整 query 分类与统计」：explanation(79)/generation(51)/debugging(9)/capabilities(4)/appreciation(4)
  - 补充 Pilot Study D 关键数据：Cohen's d=1.11 (task time, p=0.03), d=1.7 (quiz score, p=0.003)，主研究采用保守估计 d=0.85
  - 更新 updated 日期至 2026-06-07
- 更新概念页: Skill-Formation（在「认知投入被外包」下新增「时间投入 ≠ 认知投入」校准小节）
- 更新概念页: Cognitive-Offloading（新增「时间投入 ≠ 认知投入:来自 RCT 的校准」完整小节，含四组对比表与干预建议）
- 更新概念页: AI-Interaction-Patterns（新增「代码采纳方式的独立分析」小节，含 Figure 13 四组对比与 active time 反直觉相关性）
- 三页概念页状态从 draft 提升为 reviewed
- **强化**:将「手抄代码 = 防认知外包」的常见误解用 RCT 数据纠正，认知外包的干预焦点从「形式动作」(禁止粘贴/必须手敲)转向「实质动作」(强制解释/独立调试)
- **校准**:此前 source-summary 和概念页隐含地假设"手抄比粘贴更有利于学习"——原始论文数据否定了这一假设，已在各页面标注
- **互补**:新增的「代码采纳方式」分析独立于六种交互模式，形成「怎么用 AI」(交互模式)与「怎么采纳 AI 输出」(代码输入方式)两个正交维度
- **矛盾/待观察**:1. 手抄 vs 粘贴无差异的结论基于 n=9+9 的小组，统计功效有限，需要更大样本复现;2. "基本自己写"组(n=4)同时速度较快且高分，其具体行为细节(是否也用了 AI 概念辅助)在论文中展开不足

## [09:28] ingest|摄入论文《How AI Impacts Skill Formation》(Shen & Tamkin, Anthropic Fellows 2026)
- 创建 source-summary: `sources/2026-05-02-How-AI-Impacts-Skill-Formation`
- 创建实体页: Judy-Hanwen-Shen, Alex-Tamkin
- 创建概念页: Skill-Formation, Cognitive-Offloading, AI-Interaction-Patterns
- 更新实体页: Anthropic（新增 Fellows Program 研究输出小节，串联 Learning Mode 产品策略）
- 更新 index.md（新增资料摘要、人物、概念条目；概念新增"人机协作 / 技能形成"小节）
- 未发现与既有内容的强矛盾;**校准**:本论文在"学新库"场景未复现 Copilot 研究的"junior 提速 55.5%"，对"AI 让新手提速"的笼统说法划了边界(不需要新知识时才成立)。已在 source-summary 内"与已有内容的关系"小节标注。

## [10:15] ingest|摄入《工资只要300块一个月的生鲜店长助理》(Agent特区论坛第20期复盘，崔老板整理)
- 创建 source-summary: `sources/2026-04-05-工资只要300块一个月的生鲜店长助理`
- 创建实体页: 米总(David，案例实施者), 崔老板(案例整理者/绿化采购询价实践者)
- 创建概念页: AI-as-Translator(AI仅做翻译官的架构模式), Zero-Barrier-Interface(零门槛交互设计), Skill-Boundary(Skill框死功能范围的安全约束)
- 更新概念页: Problem-First-AI-Adoption(补充米总五决策工程实现、关联新概念)
- 更新 index.md: 添加资料摘要/人物/概念条目
- 未发现与既有内容的矛盾;**强化**:本文是 `sources/2026-04-06-马工-别学AI了直接用起来` 中核心案例的一手原始资料，提供了马工摘要中未涵盖的五个关键设计决策、成本结构、功能模块、六步复刻法等技术细节