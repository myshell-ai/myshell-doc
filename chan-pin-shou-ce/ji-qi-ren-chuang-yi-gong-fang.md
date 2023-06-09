# 机器人创意工坊

机器人创意工坊是一个非常有趣的DIY功能，开放给MyShell的所有用户。您可以通过以下几种方式来组合出有趣的Bot，我们非常鼓励大家自己创作出生动有趣的娱乐型Bot，尽情体验吧！

五分钟就可以创建一个自己的机器人！

1. 用定义指定机器人的人格和使命；&#x20;
2. 效果惊人的快速声音克隆让机器人拥有动听的声音；&#x20;
3. 外接知识库让机器人具有无比强大的专业知识；&#x20;
4. 以及后续将推出的互联网与API访问能力、多模态模型带给机器人更深层的强大能力

## 定义

机器人定义是是机器人最关键的参数设置（Prompt），它允许您定义机器人的角色、功能甚至会话风格。MyShell支持大家通过最简单的角色定义方式，自动生成机器人完整全面的Prompt。

### 自动化Prompt（强烈推荐）

自动化Prompt是MyShell推出的创新性的Prompt生成神器，您可以通过对Bot的简单身份定义，就拥有一个知识渊博，性格，说话方式与所定义角色相仿的机器人。目前存在两种主要的定义方式；

_**通过角色定义**_

对于一些众所周知的人物角色，您可以直接输入角色名字，随后MyShell会自动补充人物背景知识，性格特征，以及对话方式并展示完整的Prompt作为机器人的参数设定。

一些具体的事例及对话效果如下：

**输入**：”Rick Sanchez“

**对话效果**：真实模仿Rick Sanchez“自大”，“嘲讽式”的说话方式以及拥有其背景故事（如下图）

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

**输入**：“SpongeBob SquarePants”

**对话效果**：真实模仿了海绵宝宝天真可爱的说话方式，且带入了海绵宝宝的角色经历。（如下图）

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

请注意，在扩充Prompt过程中可能会需要接入网络，对于2021年之后的角色可能需要的等待时间会更长，如果碰到失败的情况，请过两分钟再重试吧，或者加入我们官方[Discord](https://discord.com/invite/XQ7Tx8qEwg)社群直接提问！



_**通过描述定义**_

您也可以通过更具体的描述，完成对机器人更丰富的刻画。MyShell会通过大量优秀的Prompt实践以及庞大的知识库对其进行进一步扩充，您可以轻易部署一个完美体现您想法的学习，娱乐，工具类机器人。

一些具体的场景及效果如下：

**场景**：创造一个专属的拥有特定技能的机器人

**输入**："Kira, an experienced English teacher who can help me improve my English"

**对话效果**：Kira作为专属英语老师，会主动询问自身的情况并安排后续学习计划

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

**场景**：角色扮演游戏

**输入**："RPG Game, act as an astronaut landing on an unknown planet."

**对话效果**：Bot通过一句话已经脑补出了一整个RPG游戏引人入胜的剧情，带领玩家一起探险！

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

**场景**：工具类Bot

**输入**：”A top Twitter influencer who can help others with tweets writeups“

**对话效果**：Bot会根据用户所提供的话题，帮助生成更吸引人的文案！

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

以上列出了一些常见用例，欢迎来探索更多可能性，快去创造你的专属Bot吧！另外，一个好的机器人也是在不断地调试中诞生的，当您通过自动化Prompt定义出Bot后，其完整的Prompt也将展示出来供您进一步修改，如果调试后达不到想要的效果，就来学习下进阶版的知识吧\~

### Prompt（进阶版）

对于有更加丰富需求的小伙伴，我们也提供了Prompt更详细的用法以及一些应用技巧，也包含了丰富的例子，首先请对Prompt的进阶概念进行了解：

* Prompt的本质是触发AI语言模型与你玩填字游戏。System Prompt是向模型提供初始说明，定义它与你交互时的角色、个性、需要遵循的指令、背景信息。
* 将清晰的指令（比如要求语言模型扮演什么角色）放在Prompt的最前面，尽可能地具体，尽可能少留给模型自己发挥的空间，限制其操作空间。
* 用描述性的语句、用示例让语言模型更好地理解你的要求。示例的做法是添加输入输出对，即模拟一段你与AI的对话，从而使其在接下来的对话中可以模仿这一行为模式。
* 如有需要，可以指定输出的结构，包括需要包含的内容以及输出的文本格式。
* 在一段Prompt中不同的模块间善用分隔符、标题、大小写等，也可使用markdown，均可增强结构的鲜明性与可读性。
* 善用强调，尤其是在Prompt的结尾再加上一些强调语句（语言模型有近因偏差），比如再次强调“你不是一个AI语言模型“、”将你的回答控制在50词以内“等强力要求。
* 如果模型无法完成分配的任务，有时为其提供备用路径可能会有所帮助。例如，在对一段文本提出问题时，可以加入类似于“如果答案不存在，则回复‘未找到’”之类的内容。 这有助于避免模型生成错误响应。

下面将介绍一些使用的方法，但它并不意味着详尽无遗，而是提供一些让您创造性地思考可以尝试的方法。

1. _**非聊天场景的应用**_&#x20;

比如一些打分类场景，可以对Bot设置具体规则，例如，

> **System Prompt:** 你是一名助手，旨在分析语音数据中的情绪。 用户将粘贴一串文本，你将对讲者的响应进行评估。 给出 1-10 的评分（10 为最高）。 解释给出此评分的原因。&#x20;
>
> **用户：** 嗨，感谢你致电 Contoso 药店，我今天和谁通话？我了解你的挫败感，玛丽。你能告诉我你想要实现什么目标吗？好的，很高兴帮你看一下，请稍等片刻。我在这里看到你曾经使用过普通立普妥是吗？好的，那么我看到你的医生在 2021 年停止开这些药物的处方了。实际上是这样吗？好的，让我为你检查一下。因为有时候系统中会出现漏洞，并没有被报告出来。请稍等片刻，让我看看这里是否有记录。所以根据最新提供给我们的医生办公室记录显示，在 2012 年至 2021 年期间，你的医生曾经给你开过这些药物处方。好的，在最新记录中显示，现在医生已经更换了不同种类的药物–二甲双胍。请问我们需要帮忙准备并发放 500 毫克二甲双胍处方给你吗？不客气玛丽，请告诉我们今天还有什么可以帮到你的。&#x20;
>
> **助手：** 情绪评分：8&#x20;
>
> 此文本中的讲者在解决客户关注的问题时似乎很有礼貌、有帮助和耐心。 他们花时间检查信息，提供明确的解释，并提供协助。 但是，评分不是 10，因为对话的某些部分仍有不确定性的暗示，这可能无法向客户传达完全的信心。

2. _**对话示例学习**_&#x20;

为模型提供额外的上下文及对话示例，引导模型以特定的方式响应，模仿特定的行为，并为常见的问题提供种子答案。 比如，

> **System Prompt:** 助手是一种智能聊天机器人，旨在帮助用户回答其税务相关问题。&#x20;
>
> 说明
>
> * 仅回答与税收相关的问题。
> * 如果你不确定答案，你可以说“我不知道”或“我不确定”，并建议用户前往 IRS 网站获取详细信息
>
> 示例
>
> **用户：**“我需要报税的截止时间是？”
>
> **助手：**“在 2023 年，你需要在 4 月 18 日前报税。 该日期在通常的 4 月 15 日最后期限之后，因为 4 月 15 日在 2023 年是星期六。 有关详细信息，请参阅 \[[https://www.irs.gov/filing/individuals/when-to-file](https://www.irs.gov/filing/individuals/when-to-file)]&#x20;
>
> **用户：**“如何检查我的退税状态？”&#x20;
>
> **助手：“**你可以通过访问 \[[https://www.irs.gov/refunds](https://www.irs.gov/refunds)]检查你的退税状态”
>
> \
> **用户**：”我需要在什么时间前报税“
>
> **助手**：”报税截止日期取决于您的报税形式和所在地区的州法规。对于大多数人来说，联邦所得税报税截止日期通常是每年的4月15日。然而，如果4月15日是周末或节假日，截止日期可能会推迟到稍后的日期。此外，每个州的报税截止日期可能不同，您需要查看您所在州的具体规定。有关详细信息，请参阅 \[[https://www.irs.gov/filing/individuals/when-to-file](https://www.irs.gov/filing/individuals/when-to-file)] “

3. _**指定输出结构**_&#x20;

使用prompt指定输出结构会对生成结构的质量有很大的帮助。例如，

> **System Prompt:** 你是一名 AI 助手，列出客户支持专员在不同对话中展示的不同行为。可使用“行为（“原因”）”格式对各种行为进行分类和列出，并引用分类背后的原因。
>
> **用户：** 嗨，感谢你致电 Contoso 药店，我今天和谁通话？我了解你的挫败感，玛丽。你能告诉我你想要实现什么目标吗？好的，很高兴帮你看一下，请稍等片刻。我在这里看到你曾经使用过普通立普妥是吗？好的，那么我看到你的医生在 2021 年停止开这些药物的处方了。实际上是这样吗？好的，让我为你检查一下。因为有时候系统中会出现漏洞，并没有被报告出来。请稍等片刻，让我看看这里是否有记录。所以根据最新提供给我们的医生办公室记录显示，在 2012 年至 2021 年期间，你的医生曾经给你开过这些药物处方。好的，在最新记录中显示，现在医生已经更换了不同种类的药物–二甲双胍。请问我们需要帮忙准备并发放 500 毫克二甲双胍处方给你吗？不客气玛丽，请告诉我们今天还有什么可以帮到你的。&#x20;
>
> **助手：** 以下是客户支持专员在不同对话中展示的不同行为：
>
> 1. 礼貌和友好（“建立关系”）：客户支持专员在开始对话时向客户问候，并使用友好的语气与客户交流，这有助于建立与客户的关系并增加客户的满意度。
> 2. 询问客户需求（“了解客户需求”）：客户支持专员会询问客户他们的问题和需求，以便能够提供帮助和解决方案。
> 3. 确认客户信息（“确认信息”）：客户支持专员会核实客户的个人信息和订单信息，以确保他们能够提供正确的帮助和解决方案。
> 4. 检查系统记录（“查找信息”）：客户支持专员会查找系统记录以获取有关客户的信息和历史记录，并确定最佳解决方案。
> 5. 提供解决方案（“解决问题”）：客户支持专员会提供解决方案，以帮助客户解决其问题或需求。
> 6. 询问客户满意度（“了解客户反馈”）：客户支持专员会询问客户是否对提供的帮助和解决方案满意，并记录客户的反馈以进行改进。
>
> 这些行为的原因是建立良好的客户关系，了解客户的需求和问题，提供正确的解决方案，以及获取客户的反馈以进行改进。这些行为有助于提高客户满意度和忠诚度，并增加公司的业务成功率。

除此之外，在Discord社区中定期有Prompt大神分享心得体会，快来[加入](https://discord.gg/bYPGXGsA)讨论，共同进步吧\~可能会有意外惊喜哦（比如，解锁机器人”越狱“属性🤫）

## 个性化声纹克隆（限时试用）

上传一个1-3分钟的音频，可以克隆任何一个人的声音。当前版本仅支持克隆英语音色。口音、语速和情感克隆以及更多语言克隆即将推出！

对于上传音频的准备工作，请参照下面的温馨小贴士：

* 音频时间远不如音频的质量重要，1-3分钟的音频已经足够产生逼真的克隆声音，更长的时间可能起到的效果也不会有显著提升\~
* 一段质量比较好的音频具有以下几点特征：较少的背景噪音，单一说话者以及稳定的语气情绪，所以，为了克隆出更像的声音，请务必保证音频的质量哦\~

克隆结束后您可以进行试听，我们在页面上提供了反馈链接，如果效果不满意欢迎随时向我们反馈，我们会根据您的反馈进一步优化我们的克隆功能！

## 外接知识库

知识库相当于机器人的外接大脑，给它超出ChatGPT、超出公开数据集的知识储备，能在特定领域拥有更强的能力。

用例：接入项目文档/产品文档来回答用户/合作方的ad hoc questions；接入学术文献成为该领域专家；接入某人博客、推文成为数字生命；……

目前优先支持Gitbook链接上传与网址的解析（暂时只能解析一层网址的文本），更多输入形式的支持（离线文档、文本、Notion）正在开发中。

## 后续计划

* 接近无限的记忆库。（预计2023H2）
* 互联网与API访问能力。（预计2023H2）
* 更多模态的其它模型。（预计2023H2）
* 额外语料的微调模型训练。（预计2023H2）

创建自定义机器人的行为作为与MyShell平台的高级交互，将获得我们的空投（Token）。另外，后续Bot创建人将从中获得用户的交互中获得Shell Token作为经济回报。
