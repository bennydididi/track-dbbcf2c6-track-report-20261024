这个产品帮助【已有文字稿的独立播客主和小型制作工作室】，在【每集剪完准备发布】时，解决【整理节目简介、章节、标题和多平台发布文案耗时、反复改格式的问题】。

# 播客发布素材助手：需求成立，独立收费待验证，暂不优先 SEO

调研日期：2026-10-24。以下结论仅针对“已有文字稿 → 单集发布素材包”。

## 一、首屏决策

### 钉死的研究对象

| 项目 | 本次固定范围 |
|---|---|
| 谁 | 已定期发布、有可用文字稿的独立播客主；兼顾小型制作工作室，暂不承接要求复杂的媒体机构 |
| 输入 | 粘贴文字稿、TXT 或 SRT；可补栏目语气、嘉宾姓名和已确认的资源链接 |
| 输出 | 单集节目简介（show notes，含摘要、要点、资源列表）、章节标题、候选标题、社媒发布文案；纯文本/Markdown/HTML 导出 |
| 唯一任务 | 把**已完成的文字稿**整理成一集能审阅后发布的文字素材包 |
| 交付边界 | 只有带时间码的输入才输出可核对的章节时间戳；普通 TXT 只给章节顺序。链接只使用输入中已确认的地址，不猜链接 |
| 远程成交 | 浏览器收稿、生成、导出即可完成交付；符合中国小团队做出海 SaaS 的范围 |

### 三维决策与下一步

| 维度 | 判断 | 决定性依据与限制 |
|---|---|---|
| 有无相关需求 | **有；当前小切口证据中等** | 主播明确使用“Descript 文字稿 → Gemini 简介”；说明任务存在，也说明通用 AI 已能承接。[现用流程原帖](https://www.reddit.com/r/podcasting/comments/1wtmxzu/tools_processes_youve_found_helpful/) |
| 切口能否独立收费 | **待验证，尚未通过同切口 PMF 门槛** | Podnotes 有文字稿预览和付费入口，AfterCast 接收文字稿但仍标早期开放；已付费客户、收入及续费证据**未找到**。[Podnotes](https://podnotes.org/)、[AfterCast](https://www.aftercast.io/) |
| 是否优先靠 SEO | **暂不优先；仅保留英语小规模试验** | US 两个生成器词各返回月搜 10；月搜 480 的宽词以教程为主。免费直接替代品存在，原始 SERP 全部不足十条，另有数据缺失。[搜索量供应商](https://api.pxany.com/v1/keyword-volumes)、[宽词搜索入口](https://www.google.com/search?q=podcast+show+notes&gl=us&hl=en)、[免费直接工具](https://sotto.to/tools/podcast-show-notes-generator/) |

**当前建议：留在验证池，不进入长期 SEO 建站投入。** 先用真实文字稿验证：用户是否愿为“保留栏目语气、检查来源、一次导出多种格式”另付钱。现有公开证据不足以证明所有免费方案已让用户满意，也不足以证明当前切口已有稳定付费市场。

**会改变决定的未知：** 有稿用户是否仍每集反复改文案，并愿意为减少修改付费；如果只需要一版摘要，免费工具和现用 Gemini 流程已经构成强替代。[现用流程](https://www.reddit.com/r/podcasting/comments/1wtmxzu/tools_processes_youve_found_helpful/)、[免费简介工具](https://www.podcastools.com/ai-show-notes-writer)

**下一步验证（实验设定，尚未执行）：** 招募已有稿且仍有修改负担的用户，展示同一份稿在本工具、免费工具、现用 AI 流程中的输出与修改时间；先收单集小额费用，再观察下一集使用。首付、复用、续费分别验收，见第五节。

### 专员原分逐项核实

原分来自用户指定的初步报告与第四批原报告；两份报告的公开 HTTPS 链接**未找到**。以下为研究判断，均为 5 分制；综合分放附录。

| 项目 | 专员原分 | 核实后分 | 关键依据 |
|---|---:|---:|---|
| ①需求真实 | 4 | **3** | 有直接有稿流程，但缺“该流程仍痛苦”的近期独立样本；原热帖主要是转写或发布操作，不能全算本切口。[有稿用户](https://www.reddit.com/r/podcasting/comments/1wtmxzu/tools_processes_youve_found_helpful/)、[转写热帖](https://www.reddit.com/r/podcasting/comments/1v9txj6/transcribing_episodes_is_literally_killing_my/) |
| ②付费意愿 | 4 | **2** | 同切口有标价/试用，实际付费与留存**未找到**；整套音视频工具收费不为当前小功能加分。[Podnotes](https://podnotes.org/)、[AfterCast](https://www.aftercast.io/) |
| ③好服务 | 4 | **3** | 用户不一定专业，但语气、链接与格式需要审阅；技术类主播追求有上下文的深链接，不能假定“要求不高”。[具体痛点](https://www.reddit.com/r/podcasting/comments/1es8ljo/whats_your_workflow_for_generating_good_show_notes/) |
| ④小团队做得动 | 5 | **5** | 文本进、文本出可实现；Sotto 展示浏览器内处理及 Markdown 导出。评分为范围判断，未包含自动转写、分发集成。[同类形态](https://sotto.to/tools/podcast-show-notes-generator/) |
| ⑤形态简单 | 4 | **4** | 表单与文字导出成立；模板、来源核查和跨格式预览增加少量复杂度。[免费直接表单](https://www.podcastools.com/ai-show-notes-writer) |

## 二、判断依据：任务存在，但痛点和付费要拆开

### 用户原声与反证

日期、赞/评论数来自专员的 Arctic Shift 缓存；本轮打开原帖核正文，页面相对时间不用于倒推日期。热度为**缓存值**，不是当前值。

| 用户、日期、热度 | 原话与现用工具 | 支持什么／不能证明什么 |
|---|---|---|
| 独立访谈主播；2026-09-29；1 赞/7 评论 | “Google Gemini - Generating show notes from Descript transcripts”。[原帖](https://www.reddit.com/r/podcasting/comments/1wtmxzu/tools_processes_youve_found_helpful/) | **与本次输入输出完全对口**。已在做此任务；未说简介生成不满意，也未说为简介另付费。Descript/Gemini 的付费状态未找到 |
| 小型播客主；2026-06-09；5/7 | “writing the show notes, coming up with a title and description”；问工具、助理或模板。后续更强调剪辑片段。[原帖](https://www.reddit.com/r/podcasting/comments/1u0yrdw/) | 支持发布前写作负担；未确认已有稿。不能把片段剪辑的抱怨和预算算进本任务 |
| 技术类长访谈主播；2024-08-14；热度未找到 | “the whole process is enormously time-consuming”；想要有上下文、可跳转的简介。回复指出 RSS 描述换行及链接问题。[原帖](https://www.reddit.com/r/podcasting/comments/1es8ljo/whats_your_workflow_for_generating_good_show_notes/) | 支持“摘要之外还要链接、格式”的缺口。超过近半年，不计近期频次；未找到独立软件付款自述 |
| 发布流程调研者；2026-09-30；16/55 | 主帖自称调研；评论提到到各门户复制文案、检查发布状态。[原帖及评论](https://www.reddit.com/r/podcasting/comments/1wu6rv3/podcasters_who_publish_regularly_what_actually/) | 评论支持发布工作重复，主帖不是买家求购。**复制/调度/上传不属于本工具交付**，不据此承诺解决整个发布流程 |
| 文字稿清理中的主播；2026-07-29；25/54 | 抱怨说话人被合并、清理转写耗时。[原帖](https://www.reddit.com/r/podcasting/comments/1v9txj6/transcribing_episodes_is_literally_killing_my/) | **排除加分**：缺的是好文字稿，本工具从已有可用稿开始 |
| 刚开播的用户；2026-08-30；12/26 | 希望把完整转写放进简介，要求尽量免费。[原帖](https://www.reddit.com/r/podcasting/comments/1w22fjl/recommendations_for_podcast_transcriptions/) | **排除加分**：音频转文字需求，并非文字稿生成发布包 |

另有 2026-09-26“简介太像垃圾营销文案”帖，缓存为 17/16，内容称已把文字稿交给 AI、最终回到自己写；本轮公开页两种地址均未取到正文，因此只留作访谈线索，**不作为已核实需求或差评加分**。[待复核原帖](https://www.reddit.com/r/podcasting/comments/1wqmdgc/)

**不能把“有提及”当成“有痛点”。** 重算专员缓存得到：r/podcasting 2,925 帖、r/Podcasters 661 帖；简介/单集描述正则命中 64 帖，Castmagic 命中 2 帖，去重并集 65 帖。它们包含宣传、教程、转写、无痛现用流程，**不是 64 个有稿付费需求**。本轮 Arctic Shift 因 DNS 失败，未重拉半年全量；使用的是 2026-04-23 至 10-23 的历史缓存。[版块一](https://www.reddit.com/r/podcasting/)、[版块二](https://www.reddit.com/r/Podcasters/)、[原采集接口复查入口](https://arctic-shift.photon-reddit.com/api/posts/search?subreddit=podcasting&after=2026-04-23&limit=100)

## 三、现有解法与独立收费缺口

### 直接竞品：供给已存在，收入验证仍缺

以下只比较能直接接收已有文字稿的解法。官网功能与价格是卖方陈述；本轮未完成登录后的生成质量、结账与续费测试。

| 解法 | 官网可核实内容 | 收费/PMF 核实与切入含义 |
|---|---|---|
| Sotto 免费生成器 | 文字稿/提纲 → 摘要、要点、章节、引用、社媒和邮件文案；规则提取、浏览器处理、Markdown 导出。[工具页](https://sotto.to/tools/podcast-show-notes-generator/) | **免费**；页眉的 $49 是其 Mac 转写产品，不能当成本生成器收费。真正生成质量、活跃用户及付费客户未找到 |
| Podcastools | 粘贴文字稿、选风格和要点数量；免费、无需登录；明确不补链接与时间戳。[工具页](https://www.podcastools.com/ai-show-notes-writer) | 证明基本摘要供给充分；完整素材包、来源校验有可试缺口。付费客户数、收入、流量、融资未找到 |
| Podnotes | 文字稿免费预览；导出、历史与完整包放在升级路径；Starter 同时显示 $12.99 与 $9.99/mo，两价适用账期/优惠未核实。[官网定价区](https://podnotes.org/#pricing) | 标价并不证明成交；套餐同时计音频分钟，音频流程还写“启用后可用”，单纯文字稿付费 PMF **未找到**。客户数、收入、续费、独立流量、融资未找到 |
| AfterCast | 粘贴/上传文字稿，输出简介、博客、邮件和社媒，强调栏目语气；标早期开放、7 天试用。[官网](https://www.aftercast.io/) | 仅检索缓存可读，直接打开返回 402。可核实付费价、付费客户、收入、续费、独立流量、融资**未找到**；不能把示例人物算客户 |
| 用户现用 Gemini 流程 | 已有 Descript 文字稿，再生成简介。[用户原帖](https://www.reddit.com/r/podcasting/comments/1wtmxzu/tools_processes_youve_found_helpful/) | 对口的实际使用证据，也是低切换动力的反证；是否愿为模板/导出再付钱未找到 |

**小团队可试的缝隙是“少改、可核对、直接粘贴”，不是再做一个摘要按钮。** 第一版可保存栏目范文与专名词表，让每段要点回指输入位置；带时间码时保留引用，资源链接必须人工提供或确认；同时预览纯文本与 HTML。格式/深链接痛点有用户证据，Podcastools 明确不提供链接与时间戳；但 Sotto 已覆盖多种文案，所以“多输出”本身不足以形成差异。[用户格式问题](https://www.reddit.com/r/podcasting/comments/1es8ljo/whats_your_workflow_for_generating_good_show_notes/)、[Podcastools 边界](https://www.podcastools.com/ai-show-notes-writer)、[Sotto 覆盖范围](https://sotto.to/tools/podcast-show-notes-generator/)

**尚无充分止损证据，也没有扩建依据。** 没有证明用户普遍满意免费方案；同样没有证明他们愿为上面的差异付钱。专业工作室可能提出更严格审校要求，因此“好服务”下调；只保留文字生成和导出，技术范围仍适合小团队。

**AI 越强，交付会更好，但付费理由可能变弱。** 已有通用 AI 流程说明“生成能力”本身容易被替代；要验证的产品价值是固定栏目规范、事实回查和省掉格式修改，不能声称通用 AI 无法记模板。[真实流程](https://www.reddit.com/r/podcasting/comments/1wtmxzu/tools_processes_youve_found_helpful/)

## 四、能承接的搜索词与竞争判断

### 同一发布任务，合并判断，不按国家或子功能累加市场

搜索量来自用户提供的 2026-10-24 PXAny 快照；单位为**该国 Google 月搜索量估计**，不是独立买家数。原始搜索量响应未保存，本轮 DNS 失败无法重测；脚本把 `avgMonthlySearches=null` 映射成 0，故旧“供应商返回0”存在空值误归风险。正数只沿用原记录，不合并近义词推算人数。[搜索量接口](https://api.pxany.com/v1/keyword-volumes)

| 同一任务内的搜索表达 | US | UK | CA | AU | 页面是否能直接承接 |
|---|---:|---:|---:|---:|---|
| podcast show notes generator | 10 | 10 | 10 | 10 | **条件承接**：有稿用户可用；不能满足只拿音频来的人 |
| show notes generator | 10 | 10 | 10 | 10 | 条件承接；与上行近义，不能直接相加 |
| podcast show notes | 480 | 30 | 30 | 30 | 信息/教程/节目导航混合；工具页不能完整承接，不计成购买量 |
| podcast episode title generator | 30 | 10 | 10 | 10 | 输入可能只有主题；本方案必须有文字稿，不全算直接目标流量 |
| transcript to show notes | 0† | 0† | 0† | 0† | 任务精确；US 原样本严重偏题，不能用来判断竞品强弱 |
| show notes from transcript | 0† | 0† | 0† | 0† | 任务精确；仍做了核心词 SERP，低量不等于需求不存在 |

表内来源：[PXAny 月搜快照接口](https://api.pxany.com/v1/keyword-volumes)；†＝旧记录标“供应商返回0”，真0与空值归0无法重建。完整逐词原值、状态、国家、任务组和复查链接见证据包 `keyword-audit.csv`；**不引用转写、剪辑、内容搜索的量**。

| 需求组 | 实际 SERP 样本与直接对手 | 对 SEO 的含义 |
|---|---|---|
| 简介/发布包生成 | US `podcast show notes generator` 样本 9 条：前部含 ShowNotesGenerator、Swell、Podsqueeze、Recast，另有 Riverside、Descript；核过的入口主要接音视频。US `show notes generator` 样本 9 条，另出现 Sotto 和 LumiClip。[词一](https://www.google.com/search?q=podcast+show+notes+generator&gl=us&hl=en)、[词二](https://www.google.com/search?q=show+notes+generator&gl=us&hl=en)、[音视频入口例](https://shownotesgenerator.com/)、[文字稿入口](https://sotto.to/tools/podcast-show-notes-generator/) | 有成熟供给是需求信号；可比小站也存在。仅“省转写费”无法覆盖所有搜索者；免费入口使商业转化更难验证 |
| 简介写法/概念 | US `podcast show notes` 样本 8 条，多为教程、行业内容与 Reddit；DE `Podcast Shownotes` 返回 70，也以解释/写法为主。[US](https://www.google.com/search?q=podcast+show+notes&gl=us&hl=en)、[DE](https://www.google.com/search?q=Podcast+Shownotes&gl=de&hl=de) | 可写教学入口并嵌工具，不能用这些量代替付费生成器流量 |
| 单集标题/描述 | US 标题词样本 9 条，含免费标题工具；描述词同样混入主题输入型产品。[标题 SERP](https://www.google.com/search?q=podcast+episode+title+generator&gl=us&hl=en)、[描述 SERP](https://www.google.com/search?q=episode+description+generator&gl=us&hl=en) | 标题、描述属于素材包组成部分；另开大量独立页面会重复覆盖意图 |
| 章节/社媒文案 | US 章节词样本 9 条，含整套音视频工具；`podcast chapters from transcript` 为 8 条。社媒词与内容再利用工具混合。[章节](https://www.google.com/search?q=podcast+chapter+generator&gl=us&hl=en)、[有稿章节](https://www.google.com/search?q=podcast+chapters+from+transcript&gl=us&hl=en) | 仅带时间码的稿才能交付可信时间戳；不得把自动转写、视频切片或分发需求算进来 |

排名来自所给第三方国家 Google 快照，不是本轮独立实时排名保证。**已做的 105 组全部不足十条：87 组为 9 条、17 组为 8 条、1 组为 7 条**；未逐页实测所有结果功能，故不给“完整前十竞争弱”的结论。[SERP 供应商入口](https://api.pxany.com/v1/serp)

**国家优先级：只保留英语验证入口。** 德语有相关解释性需求，荷语宽词返回 20，但未发现足以优先布局的正数工具词；西、意多数旧0，法、日、韩大量未返回。翻译质量和当地说法仍需母语核实，不能据此判定这些市场没人需要。[DE 复查](https://www.google.com/search?q=Shownotes+Generator&gl=de&hl=de)、[NL 复查](https://www.google.com/search?q=podcast+shownotes&gl=nl&hl=nl)、[数据接口](https://api.pxany.com/v1/keyword-volumes)

原样本中，US `transcript to show notes` 出现词典、展会等偏题结果，FR 对应转换词出现词典/服饰页，JP 一个文字稿转简介词出现政府站点；已从竞争推断中排除。补充网页搜索可找到相关日法工作流文章，说明偏题样本不能解释成需求不存在；补搜不冒充当地 Google 完整前十。[日语工作流](https://memolith.me/blog/podcast-transcription-shownotes)、[法语工作流](https://sozai.app/fr/podcast-episode-into-show-notes/)

## 五、最小验证与停止条件

以下数字均为**本次建议的实验规则，不是已发生结果或行业基准**。现阶段只做收稿、生成、审阅和导出，不建设转写/剪辑/自动发布系统。

| 验证 | 动作与建议门槛 | 明确不能替代的指标 |
|---|---|---|
| 首付 | 找 20 位已有稿、仍需修改简介的合格用户；给同稿对比，试收 **$3/集**。至少 3 位真实购买并用于发布，才继续产品化 | 填邮箱、夸赞、免费生成、购买整套转写软件，都不算本切口首付 |
| 复用 | 首付者下一集发布时，至少 2 位再次导入**新稿**并实际导出；与其旧流程比，记录修改用时和关键错误 | 同一集反复点生成、套餐内再次使用不算再次付款；双周/月更用户按实际更新周期等候 |
| 再购/续费 | 若按集收费，看下一集是否产生第二笔实付；如试 **$9/月、4 集**，要等首个续订账期，看真实续扣、退款与取消 | 月内第二次使用只算复用，不算续费；续订周期前一律写“未到期”，不能提前宣称留存 |
| SEO | 首付有信号后，只做一个英语工具页及同任务教程；观察 8 周收录、精确意图曝光、访问→首付，先记录基线 | 排名、曝光、访问都不能代替付费；未收录时不能把无访问解释成无需求 |

**停止/调整条件：** 完成 20 位合格用户同稿演示后不足 3 位首付，或付费者一致认为免费方案/现用 AI 已够用，停止当前独立收费假设；若有人首付但下一集不再用，先查一次性尝鲜与输出质量，暂缓订阅。数字只用于早期筛查，小样本通过也不代表 PMF 已成立。

**质量与收支：** 要点、专名、链接、时间戳应能回查输入；无时间码就不给虚构时间。逐单记录模型、支付、退款、客服与获客成本，只有净收入能覆盖这些可变成本才扩量。当前单集推理成本、支付费率、获客成本和毛利实测均**未找到**；不沿用原报告“$9/月不限集”的未验证定价。

## 附录 A：综合评分与门槛

综合评分 **68/100**，计算为 `(3+2+3+5+4)÷25×100`；原分 **84/100**（原 21/25）。这是对初评五项的等权复核，不新增一套打分，也不包含独立 SEO 可行性分。

**②付费意愿 2<3，同切口 PMF 未证明，因此不推荐直接立项扩建。** 68 分不能覆盖这个门槛；允许继续做低成本付款验证。评分依据见首屏逐项表。[同切口标价与限制](https://podnotes.org/)、[免费直接替代](https://sotto.to/tools/podcast-show-notes-generator/)

相邻机会只列出、不贡献本评分/搜索量/付费证明：音频或播客链接转文字；播客内容搜索；音视频剪辑与短视频渲染；跨平台自动上传/调度；文字生成音频播客。原报告引用的 Castmagic、Descript 整套产品收费，只用于纠正原初评证据归属，不计为“已有稿→发布包”的独立付费验证。[原对标官网](https://www.castmagic.io/pricing)

## 附录 B：国家词表与搜索量状态审计

下表是全部已提供记录的国家汇总；数字为**市场×词条数**，不是搜索次数。状态沿用原快照；旧0均加空值归0警示。核心词无论月搜多少均已查 SERP，外围词没有单市场 >200 的记录，按 SOP 不补做。[搜索量接口](https://api.pxany.com/v1/keyword-volumes)、[SERP 接口](https://api.pxany.com/v1/serp)

| 市场/语言 | 查询词数 | 返回正数 | 供应商返回0† | 未返回 | 未查询 | 已查核心 SERP |
|---|---:|---:|---:|---:|---:|---:|
| US/en | 55 | 6 | 48 | 1 | 0 | 13 |
| UK/en | 55 | 5 | 49 | 1 | 0 | 13 |
| CA/en | 55 | 6 | 48 | 1 | 0 | 13 |
| AU/en | 55 | 6 | 48 | 1 | 0 | 13 |
| DE/de | 47 | 1 | 46 | 0 | 0 | 8 |
| FR/fr | 45 | 0 | 11 | 34 | 0 | 7 |
| ES/es | 46 | 0 | 46 | 0 | 0 | 7 |
| IT/it | 45 | 0 | 43 | 2 | 0 | 7 |
| NL/nl | 47 | 1 | 46 | 0 | 0 | 9 |
| JP/ja | 45 | 0 | 1 | 44 | 0 | 8 |
| KR/ko | 45 | 0 | 0 | 45 | 0 | 7 |
| 合计 | **540** | **25** | **386** | **129** | **0** | **105** |

†“供应商返回0”为旧文件状态名，**不能保证供应商原始字段真是数值0**；源码明确把缺失/空值映射为0。认证 API 的原响应未保留，本轮无法恢复。未返回＝查询后无对应词记录；未查询＝未发起/未完成量查询。相邻机会词的新增量查询为未查询，未纳入上表。

### 核心词表摘录：不同语言表达同一任务

| 语言 | 简介/发布包 | 精确文字稿输入表达 | 相关量与缺口 |
|---|---|---|---|
| en | podcast show notes generator；show notes generator | transcript to show notes；show notes from transcript | 英语四市场生成器各 10；两个精确词旧0†；已查 SERP |
| de | Shownotes Generator；Podcast Shownotes | Shownotes aus Transkript；Transkript in Shownotes umwandeln | 宽词 70；其他列词旧0†；已查 SERP |
| fr | générateur de notes d'épisode de podcast | transformer une transcription en notes d'épisode | 列词均未返回；转换词 SERP 偏题 |
| es | generador de notas de episodios de podcast | convertir transcripción en notas de podcast | 列词旧0†；已查 SERP |
| it | generatore di note degli episodi podcast | trasformare una trascrizione in note dell'episodio | 前词旧0†，后词未返回；已查 SERP |
| nl | podcast shownotes maken；shownotes genereren | transcript omzetten naar shownotes；shownotes uit transcript | 列词旧0†；宽词 podcast shownotes 为 20；已查 SERP |
| ja | ポッドキャスト ショーノート 生成 | 文字起こしからショーノート作成 | 列词未返回；转换词 SERP 偏题 |
| ko | 팟캐스트 쇼노트 생성기 | 팟캐스트 전사문으로 쇼노트 만들기 | 列词未返回；已查 SERP |

词量来源同为 [PXAny](https://api.pxany.com/v1/keyword-volumes)。完整词表为证据包中的 `kw/`、`keyword-audit.csv` 和 `serp.md`，保留全部 540 条状态、105 组样本、核心词标记及 Google 国家复查链接。没有把同义词、各组成输出、跨国记录直接相加估计买家规模。

### 剔除与条件承接记录

| 项目 | 处理 |
|---|---|
| 音频转写、播客搜索、切片视频、自动分发 | 相邻任务；不新增量、不采付费、不贡献竞争判断 |
| podcast show notes writer | 可能求人工代写；外围词，低量未查 SERP；不能当纯 SaaS 付费流量 |
| podcast show notes / Podcast Shownotes / podcast shownotes | 信息或导航混合；保留查询记录，不计为生成器购买量 |
| 只有主题的标题/描述生成 | 本产品要求文字稿，只能条件承接；不据其量估算完整发布包市场 |
| US 两个偏题词、FR 两个偏题词、JP 一个偏题词 | 最终表标“异常/偏题样本”；不据它们下竞争弱结论 |

## 附录 C：域名、核查限制与用时

| 域名观察 | 原快照所见 | 能说明什么 |
|---|---|---|
| lumiclip.ai | 注册日期记录 2026-04-18；US `show notes generator` 样本位置 8；域名 DR 记录 4。[页面](https://www.lumiclip.ai/podcast-show-notes-generator)、[RDAP 入口](https://rdap.org/domain/lumiclip.ai) | 年轻域名出现在样本，值得继续核查；该页主要接媒体文件，且已宣传语气与多格式输出 |
| sotto.to | 注册日期记录 2025-12-05；同词位置 9；DR 记录 35。[直接文字稿工具](https://sotto.to/tools/podcast-show-notes-generator/)、[RDAP 入口](https://rdap.org/domain/sotto.to) | 当前切口的年轻域名/免费工具线索；不能推导新站一定能排上去 |
| shownotesgenerator.com | 注册日期记录 2023-03-08；US 两个生成器词样本位置 1；DR 记录 30。[页面](https://shownotesgenerator.com/)、[RDAP 入口](https://rdap.org/domain/shownotesgenerator.com) | 小站样本存在；页面明确提供免费音视频转写及简介，本次不拿其音频需求给小切口付费加分 |

注册日期与 DR 仅沿用原快照，本轮 RDAP 公开入口未能打开，独立核验**未找到**；不作为 SEO 容易或难的评分依据。最终表按独立域名、注册日期重算年龄窗口，旧 `young3` 字段仅留作原始记录。

核查边界：Arctic Shift 本轮一次 shell 请求 DNS 失败，网页接口也不可用，退回 `site:reddit.com` 搜索及逐页读取；未换 IP、未绕过限制。搜索量复查同样 DNS 失败。AfterCast 为搜索缓存证据；未取到的 Reddit 帖只列弱线索。竞品实际生成质量、付费客户、收入、续费与独立流量未找到；官网宣传的时间节省、客户规模未作本报告事实。

最终判定以 `evidence/final-decisions.json` 为唯一表源，同步 `serp.json`、`serp.md` 与 `report.html`；原始 SERP 副本、关键词、缓存命中、请求错误、页面摘录、评分及 SOP 一并打包。报告公开网页链接：**未找到**；已生成本地 HTML，当前网络受限，未完成公开发布。

用时：前置扩词约 **3 分钟**、SERP 采集约 **57 分 47 秒**，来自原任务 `timing.txt`；本轮深挖与成稿 **12 分 26 秒**，全流程墙钟约 **73 分钟**（含前置采集和阶段间隔），详见同包 `evidence/timing-audit.json`。时间为实际流程记录，不是人时或未来开发工期。
