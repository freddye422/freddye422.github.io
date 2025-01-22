去年 11 月 ChatGPT 刚推出时，许多人就预测翻译将成为最早被人工智能取代的职业之一。

今年 5 月，OpenAI 发布了一篇关于不同职业受 AI 影响程度的研究论文，其中提到口译员和翻译的工作有 76.5% 的内容暴露在人工智能的影响下，成为最可能被 AI 取代的职业之一。

然而，ChatGPT 的翻译能力是否真的能超越专业人类翻译，仍然让许多人存疑。

## 提升 ChatGPT 翻译质量的策略

为了验证 ChatGPT 的潜力，我设计了一套能够将 ChatGPT 翻译质量提升 100% 的 Prompt 提示词。经过测试，这套 Prompt 所生成的翻译结果全面超越了人类翻译的质量。这不仅是我的主观评价，而是通过 GPT-4、Bard 和 Claude2 等模型的统一评估得出的结论。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)

## 角色与任务

为了模拟专业翻译团队的工作流程，我将翻译任务分为三个阶段，每个阶段由不同的“专家角色”负责：

### 1. 翻译阶段

**参与人**：翻译专家  
**输出物**：翻译初稿  
**任务**：提供忠实于原文且流畅自然的中文初稿。

### 2. 校对阶段

**参与人**：资深校对编辑  
**输出物**：校对后的翻译稿件  
**任务**：深度校对初稿，确保语法、用词和风格的准确性与易读性。

### 3. 润色阶段

**参与人**：润色专家  
**输出物**：最终润色稿件  
**任务**：提升文本的文学美感，同时保持专业性和准确性。

## 测试案例：原文与翻译对比

以下是测试中使用的原文及不同翻译版本的对比：

### 原文（摘自《了不起的盖茨比》第一章）

> When I came back from the East last autumn I felt that I wanted the world to be in uniform and at a sort of moral attention forever; I wanted no more riotous excursions with privileged glimpses into the human heart. Only Gatsby, the man who gives his name to this book, was exempt from my reaction—Gatsby who represented everything for which I have an unaffected scorn. If personality is an unbroken series of successful gestures, then there was something gorgeous about him, some heightened sensitivity to the promises of life, as if he were related to one of those intricate machines that register earthquakes ten thousand miles away. This responsiveness had nothing to do with that flabby impressionability which is dignified under the name of the "creative temperament"—it was an extraordinary gift for hope, a romantic readiness such as I have never found in any other person and which it is not likely I shall ever find again. No—Gatsby turned out all right at the end; it is what preyed on Gatsby, what foul dust floated in the wake of his dreams that temporarily closed out my interest in the abortive sorrows and short-winded elations of men.

### 翻译稿对比

#### 翻译稿一【Google 翻译】

去年秋天，当我从东方回来时，我觉得我希望世界永远穿着制服并受到某种道德关注；我不想再进行喧闹的旅行，以特权一睹人类的内心。只有盖茨比，这个以他的名字命名这本书的人，没有受到我的反应——盖茨比代表了我不假思索地蔑视的一切。如果个性是一系列不间断的成功姿态，那么他身上就有一些华丽的东西，对生命的承诺有一种高度的敏感性，就好像他与那些记录一万英里外地震的复杂机器有关。这种反应性与那种被称为“创造性气质”的软弱易感性无关——它是一种非凡的希望天赋，一种浪漫的准备，这是我从未在任何其他人身上发现的，而且它也不是。我可能会再次找到。不——盖茨比最后一切顺利；正是这种东西掠夺了盖茨比，正是他的梦醒后飘扬的肮脏的尘埃，暂时关闭了我对人类未遂的悲伤和短暂的欢欣的兴趣。

#### 翻译稿二【我的 Prompt 加工版】

去年秋自东方归来，我渴望世间万物永守秩序，心怀道德之警醒；不再向往那些藉特权窥探心灵深处的喧嚣历险。唯独盖茨比，此书之名便是以他命名，未曾触动我的情绪——盖茨比，他所象征的一切，正是我坦率地鄙弃之所在。若言个性乃一连串得体举止的不息展现，那么他身上自有一番独特的华丽，对生命诺言的敏感度超然，宛如那些能在万里之遥感知地震波动的精密仪器。这种反应力并非那种被冠以“创造性气质”名号的脆弱易感——它是对希望的非凡恩赐，一种我在其他人身上从未见过、也大概永远不会再遇到的浪漫准备。不，盖茨比的结局其实是美好的；真正让人忧虑的是，盖茨比梦想背后飘散的那些污浊尘埃，它们暂时封闭了我对人间那些未竟之悲和短暂之喜的兴趣。

#### 翻译稿三【专业译者版】

去年秋天我从东部回来后，我恨不得世人全都穿上军装，永远向道德立正致敬；我再也不要参加各种乱七八糟的活动，再也不要窥见人们的内心。只有盖茨比例外。这本书是以盖茨比命名的，他曾经象征着我厌憎的一切。倘使人格是许多连续不断的成功行动，那么他身上自有雍容华贵的气派，他对生活的各种前景也敏感得如同一台能够测知万里之外地震的精密仪器。这种敏锐并非那种被冠以“天才气质”美誉的多愁善感，而是一种永不言弃的乐观心态，一种罗曼蒂克的随机应变，是我在别人身上未曾发现、以后也很可能不会再见到的。是的——盖茨比其实完全没有问题，使我暂时对人世徒劳之悲哀和易逝之欢欣丧失兴趣的，是盖茨比身边那些食客，是那阵在他的梦想破灭之后飘散的污浊灰尘。

---

通过以上对比可以看出，经过优化的 Prompt 能够显著提升翻译质量，甚至超越专业译者的水平。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)