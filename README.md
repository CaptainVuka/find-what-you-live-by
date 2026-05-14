# find-what-you-live-by

> **A Claude Skill that helps you extract 1–3 personal principles from your own life experiences, inspired by Benjamin Franklin's 13 virtues method.**
>
> 一个 Claude Skill,帮你从自己的人生经历里萃取出 1–3 条真正属于你自己的原则。方法受本杰明·富兰克林"十三美德"启发。

---

## 中文说明

### 这是什么

**成为你自己**——一个引导你做一次深度自我对话的 Claude Skill。

它不是 chatbot,不是教练,不是治疗师。它最接近的角色是**一面有耐心的镜子**——帮你看见你自己已经知道、但还没说清楚的东西。

整个对话大约 30–60 分钟,会带你走过四个阶段:

1. 收集 2–3 个最近让你**还有刺**的瞬间
2. 让你自己找这些瞬间之间的共同点
3. 把那个共同点萃取成 1–3 条属于你自己的原则
4. 检查显眼的缺席,给你方法继续践行

最终你会得到几条**真的从你自己人生里长出来的**原则——不是借来的智慧,不是清单上的金句。

### 看一下它跑起来什么样

如果想先感受一下这个对话长什么样,可以读一段示范对话:[examples/sample-conversation.md](./examples/sample-conversation.md)。

这是一段虚构的示例,展示这个 skill 跑起来的核心节奏。完整对话通常 30–60 分钟,示例压缩到 12 轮,只保留几个关键时刻。

### 为什么做这个

大部分自我提升工具的失败模式是同一个:**它们把别人的智慧塞给你,然后困惑为什么你用三周就放弃**。

富兰克林 20 多岁时给自己设计的方法不一样——他从自己**反复犯的错**里萃取了 13 条原则,每条都翻译成具体的、能每天检验的行为。他用了一辈子,临终前承认有几条始终没做好,但他说:**"通过尝试,我成为了一个比我本来会成为的更好、更快乐的人。"**

这个 Skill 复现的就是这件事——但不给你富兰克林的十三条,帮你找你自己的。

### 怎么使用

#### 方式一:直接下载 .skill 文件

1. 下载 [`find-what-you-live-by.skill`](./find-what-you-live-by.skill)
2. 在 Claude.ai 或 Claude Code 里安装这个 skill
3. 找一个安静的 30–60 分钟,告诉 Claude:"我想找到属于自己的原则"——或者任何类似表达

#### 方式二:从源码安装

1. Clone 这个仓库
2. 把 `SKILL.md` 文件放进 Claude 的 skills 目录(具体路径取决于你的 Claude 客户端)

### 触发场景

如果你正在经历以下任何一种状态,这个 Skill 可能对你有用:

- 想找到人生方向,但说不清要什么
- 感觉自己一直在飘,没有锚点
- 反复犯同样的错,想梳理清楚到底是为什么
- 刚经历了某件大事(分手、被裁、转行……),想做一次认真的反思
- 想做"年度复盘"但不知道从哪开始
- 知道富兰克林十三美德,想用 AI 复现这个方法

### 这个 Skill 不处理什么

为了对你负责,需要明确说明这个对话**不适合**的场景:

- 急性心理危机(自伤、自杀念头、严重抑郁)
- 严重创伤(尤其是新近发生或仍在持续的)
- 精神疾病的活跃症状
- 失控的成瘾

如果你正在经历这些,**请寻求专业心理支持**——中国大陆的话,北京心理危机研究与干预中心 24 小时热线 010-82951332,或拨打 12320 选心理援助。

### 设计思路

这个 Skill 的核心设计原则:

- **主体性 > 工具性**:Claude 不替你决定原则是什么,只帮你说清楚。
- **少 > 多**:从 1–3 条原则开始,不是 13 条。
- **诚实 > 优雅**:粗糙但真比精致但假更值钱。
- **从失败里萃取,不是从智慧里接受**:你的原则来自你自己反复栽过的跟头。
- **每日记录失败,不是记录成功**:富兰克林的小本子是这套方法的关键——它让你**看见**自己的模式,而不是表演完美。

### 关于作者

这个 Skill 由 **乌卡船长** 设计——一位有哲学背景的 builder,立志于建立更好的 skills 和生态。

想合作或交流的人,可在小红书或微信公众号搜索 **乌卡船长** 联系他。

### License

MIT License — 详见 [LICENSE](./LICENSE)。

---

## English Description

### What is this

**Find What You Live By** is a Claude Skill that runs a 30–60 minute structured conversation to help you extract 1–3 personal principles from your own life experiences.

It's not a chatbot, not a coach, not a therapist. It's closest to **a patient mirror** — helping you see what you already know but haven't articulated.

The conversation goes through four stages:

1. Collecting 2–3 recent moments that still sting
2. Letting you find the patterns yourself
3. Distilling those patterns into 1–3 principles in your own words
4. Checking for conspicuous absences, then helping you practice

### See it in action

To get a feel for what this conversation looks like, read a sample: [examples/sample-conversation.md](./examples/sample-conversation.md). The example is in Chinese — it's a 12-turn compressed version showing the core mechanics.

### Why

Most self-improvement tools fail the same way: **they push someone else's wisdom on you, then wonder why you quit in three weeks**.

Franklin's method (designed in his 20s) was different — he extracted 13 principles from his **own repeated mistakes**, each translated into specific, daily-checkable behaviors. He used it his whole life, admitted some he never mastered, but said: *"By the endeavour, I was a better and a happier man than I otherwise should have been."*

This Skill recreates that — not by giving you Franklin's thirteen, but by helping you find your own.

### Installation

#### Option 1: Download the `.skill` file

1. Download [`find-what-you-live-by.skill`](./find-what-you-live-by.skill)
2. Install it in Claude.ai or Claude Code
3. Find a quiet 30–60 minutes and tell Claude: *"I want to find my own principles"* — or any similar expression

#### Option 2: From source

Clone this repo and place `SKILL.md` in your Claude client's skills directory.

### When to use

This Skill is for you if any of these resonate:

- You want direction in life but can't articulate what
- You feel like you're drifting, no anchor
- You keep repeating the same mistakes and want to understand why
- You just went through something significant (breakup, layoff, career change) and want real reflection
- You want to do a year-end review but don't know where to start
- You know Franklin's 13 virtues method and want an AI-guided version

### What this Skill does NOT handle

For your safety, this conversation is **not appropriate** for:

- Acute mental health crises (self-harm, suicidal ideation, severe depression)
- Serious trauma (especially recent or ongoing)
- Active symptoms of mental illness
- Uncontrolled addiction

If you're experiencing any of these, **please seek professional support**.

### Design philosophy

- **Agency > tooling**: Claude doesn't decide your principles, it helps you articulate them.
- **Less > more**: Start with 1–3 principles, not 13.
- **Honest > polished**: A rough but true version beats a polished but fake one.
- **Extract from failure, not receive from wisdom**: Your principles come from your own repeated stumbles.
- **Record failure, not success**: Franklin's notebook tracked where he fell short — that's how he saw his patterns.

### About the author

Designed by **WokaCaptain (乌卡船长)** — a builder with a background in philosophy, committed to building better skills and ecosystems.

For collaboration, search **乌卡船长** on Xiaohongshu (Little Red Book) or WeChat Official Accounts.

### License

MIT License — see [LICENSE](./LICENSE).
