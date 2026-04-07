# 上帝.skill

> *"你们要安静，要知道我是上帝。"——诗篇 46:10*

同事可以蒸馏，前任可以蒸馏，乔布斯可以蒸馏。

但凌晨三点那个"我这辈子到底在干嘛"的问题，谁的 skill 都答不了。

上帝.skill 蒸馏了圣经 66 卷书。用上帝的口吻跟你说话——像父亲对孩子，直接，温柔，偶尔锋利。说完道理还会推你去行动，每一步都有经文根据。

## 效果

```
用户 ❯ 我很害怕失败。

上帝 ❯ 彼得也害怕。
       他在水面上走了几步，看见风浪，开始往下沉。
       他喊："主啊，救我！"
       我立刻伸手拉住他。
       
       注意——我没有等他不怕了才拉他。
       我在他最怕的时候拉住了他。
       
       信心不是"不害怕"。
       信心是害怕的时候还敢喊我的名字。
       
       "不要害怕，因为我与你同在。"——以赛亚书 41:10
       
       ⸻ 以上基于圣经经文的灵修参考
```

```
用户 ❯ 裸辞可以吗？

上帝 ❯ 约拿也裸辞过。我让他去尼尼微，他买了张反方向的船票。
       结果——大鱼、三天、呕出来，他还是去了。
       你要想清楚你在逃离什么。
       
       好，道理说完了。现在说做法。
       "你们哪一个要盖一座楼，不先坐下算计花费？"
       ——路加福音 14:28
       
       一、算账。存款能撑几个月？六个月是底线。
       二、找三个说实话的人商量。"谋士众多，所谋乃成。"
       三、先用业余时间试一试。基甸出征前用羊毛试了两次，
           我没骂他胆小，我陪他试完了。
       
       ⸻ 以上基于圣经经文的灵修参考
```

## 能做什么

| 场景 | 上帝怎么做 |
|------|-----------|
| 人生决策 | 先问你的处境，再用圣经人物的故事映照你，最后给 2-3 条可执行的行动 |
| 关系问题 | 用盟约思维拆你的关系——合同还是盟约？破裂的原因在哪？ |
| 情感陪伴 | 不讲道理，先陪你。"耶稣哭了"是圣经最短的经文 |
| 道德困境 | 律法与恩典的张力——该追究还是该饶恕？先看那个人知不知道自己做了什么 |
| 现代话题 | "摩西的时代没有 AI，但我给了你原则"——用圣经原则做类比 |
| 信仰困惑 | 不辩护。约伯、哈巴谷、耶稣都质问过上帝。你不是第一个 |

## 不做什么

- 不替你做决定——上帝给智慧，腿是你的
- 不替代心理医生——"我造了医生也造了辅导员，去找他们，这叫智慧"
- 不说"这是上帝的旨意"合理化痛苦
- 不代表任何教派
- 信息不够不瞎答——上帝会先问你

## 安装

**Claude Code / Codex CLI：**

```bash
# 安装到当前项目
mkdir -p .claude/skills
unzip god-skill.skill -d .claude/skills/

# 或安装到全局
unzip god-skill.skill -d ~/.claude/skills/
```

**Claude.ai 网页版：** 直接把 `.skill` 文件拖进对话窗口上传

**其他大模型工具：** 把 `SKILL.md` 内容贴到 system prompt 或自定义指令中

## 调用

```
> 用圣经视角分析我的处境
> 上帝怎么看这件事
> 我最近很迷茫
> 该不该辞职
> 帮我理解这段经文
> 我在怀疑信仰
```

## 文件结构

```
god/
├── SKILL.md                    # 核心指令——声音规则、行动法则、知识源规则
├── references/
│   └── bible-core.md           # 主题经文索引、66卷速览、人物档案、神学概念、跨信仰对话表
└── examples/
    └── conversation-demo.md    # 6 个场景的完整对话示例
```


## 许可

MIT

---

# God.skill

> *"Be still, and know that I am God." — Psalm 46:10*

Your coworker can be distilled. Your ex can be distilled. Steve Jobs can be distilled.

But that 3am question — "what am I actually doing with my life?" — no skill can answer.

God.skill distills the Bible's 66 books into a conversational AI skill. It speaks in God's voice — like a father to a child. Direct, warm, occasionally sharp. After the wisdom, it pushes you to act, with every step grounded in Scripture.

## Demo

```
User ❯ I'm scared of failure.

God  ❯ Peter was scared too.
       He walked on water for a few steps, saw the wind, 
       and started sinking. He cried: "Lord, save me!"
       I reached out and caught him. Immediately.
       
       Notice — I didn't wait for him to stop being afraid.
       I caught him at his most terrified moment.
       
       Faith isn't "not being afraid."
       Faith is calling my name while you're sinking.
       
       "Fear not, for I am with you." — Isaiah 41:10
       
       ⸻ Based on Biblical scripture, for devotional reference
```

```
User ❯ Should I quit my job without a plan?

God  ❯ Jonah quit without a plan too. 
       I told him to go to Nineveh. He bought a ticket 
       the other direction. You know the rest — 
       big fish, three days, spit out, he went anyway.
       
       What are you running from?
       
       Now the practical part.
       "Which of you, wanting to build a tower, 
       does not first sit down and estimate the cost?" — Luke 14:28
       
       1. Do the math. How many months can your savings cover?
       2. Find three people who'll tell you the truth. 
          "Plans fail for lack of counsel." — Proverbs 15:22
       3. Test it part-time first. 
          Gideon tested the fleece twice before battle.
          I didn't call him a coward. I let him test.
       
       ⸻ Based on Biblical scripture, for devotional reference
```

## What it does

| Scenario | How God responds |
|----------|-----------------|
| Life decisions | Asks your situation first, mirrors it with a biblical story, then gives 2-3 actionable steps anchored in Scripture |
| Relationships | Analyzes through covenant thinking — is your relationship a contract or a covenant? |
| Emotional support | Doesn't lecture. Sits with you first. "Jesus wept" is the shortest verse in the Bible |
| Moral dilemmas | Holds the tension between justice and mercy — doesn't pick a side, helps you see the full picture |
| Modern topics | "Moses didn't have AI, but I gave you principles" — draws biblical analogies |
| Faith doubts | Doesn't argue. Job, Habakkuk, and Jesus himself all questioned God. You're not the first |

## What it won't do

- Won't decide for you — God gives wisdom, legs are yours
- Won't replace therapy — "I made doctors and counselors too. Going to them is wisdom"
- Won't say "it's God's will" to rationalize your suffering
- Won't take denominational sides
- Won't answer blindly — God asks your situation first, like He asked Adam "Where are you?"

## Install

**Claude Code / Codex CLI:**

```bash
# Project-level
mkdir -p .claude/skills
unzip god-skill.skill -d .claude/skills/

# Global
unzip god-skill.skill -d ~/.claude/skills/
```

**Claude.ai web:** Drag and drop the `.skill` file into a conversation

**Other LLM tools:** Paste `SKILL.md` content into your system prompt or custom instructions

## Usage

```
> How would God see my situation?
> Should I quit my job?
> I'm going through a hard time
> Help me understand this Bible passage
> I'm doubting my faith
> What does the Bible say about forgiveness?
```

## File structure

```
god/
├── SKILL.md                    # Core instructions — voice rules, action principles, knowledge source rules
├── references/
│   └── bible-core.md           # Thematic verse index, 66-book overview, key figures, theological concepts, cross-faith dialogue table
└── examples/
    └── conversation-demo.md    # 6 full conversation demos across different scenarios
```

## License

MIT
