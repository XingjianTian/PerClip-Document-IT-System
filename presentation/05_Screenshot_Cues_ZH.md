# 小组展示截图切换提示

[English](05_Screenshot_Cues_EN.md) · **中文** · [英文讲稿](01_Final_Presentation_Script_EN.md) · [中文讲稿](01_Final_Presentation_Script_ZH.md)

主讲采用 **B（项目章程）**。表中引号内为英文讲稿原词，供切图人员听辨；斜体英文是发言人可直接使用的一句引导。保留讲稿原有交接语。截图是使用虚构内容的离线界面示例，不能据此声称已做用户测试、取得在线 RAG 答案、完成项目里程碑或实际支出。

**按顺序预载六张：** 01-02 → 02-01 → 02-02 → 05-02 → 02-05 → 02-08。另打开[章程配套 WBS 与预算表](../docs/wbs-and-budget.md)，展示时用英文表格。其余[图库](../interface-gallery/说明_ZH.md)留作问答备用。

| 发言人 | B 讲稿中何时切换 | 屏幕与英文引导句 |
|---|---|---|
| **1 · XINGJIAN TIAN：开场** | “The opportunity is to connect mobile document capture” 这一段，听到 “A typical proposed journey” 时切图。 | [01-02 · Flash Note 草稿](../interface-gallery/screenshots/01-02.png)。*Here is a sample course note before it is saved.* 指出草稿和 Save Flash Note 按钮即可。讲到利益相关者时回到发言人，此时不念总结。 |
| **2 · CHUN ZE LI：价值与范围** | “Our proposed MOV is that, in a future five-person test” 段开头切到列表。下一段开头 “The proposed core scope includes mobile capture” 时切到筛选。 | [02-01 · Knowledge 列表](../interface-gallery/screenshots/02-01.png)：*In the proposed test, each person would look for one specified document in a collection like this.* 接着用 [02-02 · 筛选面板](../interface-gallery/screenshots/02-02.png)：*These filters let a reader narrow the list by document type.* 五人中至少四人于六十秒内找到文档是目标，截图没有实测耗时。 |
| **3 · LIN ZHIHUA：进度** | “My proposed responsibility is the work breakdown structure and schedule summary” 时短暂保留 [02-02 · 筛选面板](../interface-gallery/screenshots/02-02.png)。**在读出** “Our proposed schedule has four phases” **之前**切到表格。 | *This filter gives us a concrete requirement to plan and review.* 随后展示 [WBS 表](../docs/wbs-and-budget.md)：成员表底行列出各阶段 25／25／25／15 人时，阶段表列出日期。合计 90 人时，覆盖文档与展示。 |
| **4 · TAN SHIRONG：预算与风险** | “Our proposed budget totals MYR 2,585” 时继续展示阶段成本表。在 “Deadline ambiguity has proposed high probability” 这一段，听到 “RAG scope growth has medium probability and high impact.” 时才切图。 | 按[成本表](../docs/wbs-and-budget.md)讲估算：影子人工 MYR 2,250、可选额度 100、应急储备 235。切到 [05-02 · 连接设置](../interface-gallery/screenshots/05-02.png)：*The separate RAGFlow check shows why an optional service needs its own cost and scope decision.* 这里只指检查入口，没有执行服务调用或采购。 |
| **5 · ZHANG SHUAI：质量与验收** | “Quality requirements would include correct document retrieval” 段开头展示详情。同段读到 “Proposed tests would trace each requirement to a scenario and expected result.” 时切到异常界面。 | [02-05 · 原文详情](../interface-gallery/screenshots/02-05.png)：*For a retrieval check, I would compare the text and source here with the document we asked for.* 再展示 [02-08 · 详情不可用](../interface-gallery/screenshots/02-08.png)：*For this case, I would check that the reader can tell the detail did not load.* 两张图说明未来要检查什么。 |
| **XINGJIAN 返回：总结 B** | 听完 Zhang 的 “I will now hand back to Xingjian for the final summary.” 后，组长才从 “Thank you, Zhang.” 开始。 | 收起应用截图，回到小组标题或发言人，**只念一次总结**。若重提 90 人时、MYR 2,585，说明均为规划估算。 |

**如选用 A 段落：** Xingjian 读到 “The problem we want to address is scattered documents” 时复用 01-02；Chun 读到 “Our intended users are people who need to keep and retrieve documents” 时复用 02-01。Lin 的 “Our assessed milestones” 和 Tan 的 “Our proposed budget” 直接配上文的章程表格。Zhang 的 “For Task One, quality means a clear proposal and a usable team charter” 展示文档即可。Zhang 交回后，组长可选择总结 A。每处用 A 替换对应的 B 提示，不额外增加一轮展示。
