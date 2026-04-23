# WisdomHealer 大佬心法疗愈

**你说出处境，AI 用大佬的脑子帮你重新看这个问题。**

不是语录展示，不是心灵鸡汤。  
是：你描述处境 → AI 找到最匹配的思维框架 → 把框架翻译进你的具体情况 → 给你一个能接着走的新视角。

> **效果：** 你说完之后，会有一种"啊，原来我卡在的不是我以为的那个问题"的感觉。

---

## 怎么用 / How to Use

直接说出你现在的状态，不需要格式，越具体越好：

> "我做了很多产品，大部分卖不出去，很迷茫"  
> "昨天被老板否定了，很丧"  
> "要不要辞职创业，纠结死了"  
> "感觉被关系吞掉了，找不到自己"  
> "有点 burnout，什么都不想干"

AI 会：
1. **重新定义你的问题本质**（不是复述，是穿透表面）
2. **匹配 1-2 位最相关的大佬**，说清楚他们是怎么想这类问题的
3. **把心法翻译进你的具体处境**（用"你"来说话）
4. **给一个可以行动的视角或问题**，让你能接着想下去

---

## 三种接入方式 / Installation

### 方式一：Cursor 用户（最省力）

```bash
git clone https://github.com/sisXin/wisdom-healer.git ~/.cursor/skills/wisdom-healer
```

重启 Cursor 后，无需任何指令，说出你的处境即可自动触发。

### 方式二：Claude Project / ChatGPT Custom Instructions

把 `SKILL.md` 的内容粘贴进 Claude 的 **Project Instructions** 或 ChatGPT 的 **Custom Instructions**，之后每次对话都会自动带上这套逻辑。

**Claude Project：** Projects → New Project → Instructions  
**ChatGPT：** Settings → Personalization → Custom Instructions

### 方式三：任意 AI 直接使用

开始对话时粘贴以下内容，然后说出你的处境：

```
请阅读以下 Skill 指令后，根据我的描述为我提供疗愈内容：
[粘贴 SKILL.md 全部内容]
[粘贴 mentors.md 全部内容]

我现在的处境是：___
```

---

## 覆盖场景 / Supported States

| 你现在的状态 | 会匹配到 |
|-------------|---------|
| 😵‍💫 迷茫 / 不知方向 | Naval Ravikant, Steve Jobs, 毛泽东 |
| 😫 内耗 / 情绪低落 | Eckhart Tolle, Pema Chödrön, Naomi Osaka |
| 💔 感情 / 关系问题 | Esther Perel, Taylor Swift, Virginia Woolf |
| 😤 不自信 / 被否定 | Kanye West, Billie Eilish, Brené Brown |
| 🚀 想突破 / 翻盘 | Elon Musk, Oprah Winfrey, Sara Blakely |
| 🧠 重大决策 | Charlie Munger, Naval, Angela Merkel |
| 😔 孤独 / 没人理解 | Drake, Billie Eilish, Michelle Obama |
| 🧩 身份冲突 / 打破标签 | Eileen Gu, Emma Watson, Simone de Beauvoir |
| 😵‍🔥 Burnout / 被压垮 | Simone Biles, Eckhart Tolle, Indra Nooyi |
| 🚫 被规则 / 期待困住 | Simone de Beauvoir, Hannah Arendt, Thatcher |
| 🔑 等待被允许 / 不敢强势 | Nicki Minaj, Margaret Thatcher, Whitney Wolfe Herd |
| 🪞 自我否定 / 完美主义 | Brené Brown, Virginia Woolf, Taylor Swift |
| 💹 加密 / Web3 / All-in | CZ 赵长鹏, 孙宇晨, 徐明星 Star |
| ⚔️ 战略困局 / 从零建立 | 毛泽东, Charlie Munger, Elon Musk |

还可以指定风格：
- 🌊 **想被接住** → Tolle / Pema / Brené Brown
- 🧊 **想被点醒** → Munger / Naval / 毛泽东 / Arendt
- 🔥 **想被激活** → Kanye / Musk / Thatcher / Nicki Minaj

---

## 人物库 / Mentor Roster（25+位）

**战略家**  
毛泽东 · Charlie Munger · Naval Ravikant

**创业者**  
Elon Musk · Steve Jobs · CZ 赵长鹏 · 孙宇晨 · 徐明星 Star · Sara Blakely · Sheryl Sandberg · Whitney Wolfe Herd · Oprah Winfrey

**思想家 / 哲学家**  
Simone de Beauvoir · Hannah Arendt · Eckhart Tolle · Pema Chödrön · Yuval Noah Harari

**运动员**  
Simone Biles · Naomi Osaka · Eileen Gu · Alysa Liu

**艺术家 / 音乐人**  
Kanye West · Billie Eilish · Taylor Swift · Drake · Nicki Minaj · Doja Cat

**政治家 / 领导人**  
Margaret Thatcher · Angela Merkel · Michelle Obama · Indra Nooyi

**关系 / 情感**  
Esther Perel · Virginia Woolf · Brené Brown · Emma Watson

---

## 文件结构 / File Structure

```
wisdom-healer/
├── SKILL.md       # AI 指令：匹配逻辑 + 输出格式（核心）
└── mentors.md     # 人物库：25+ 位的心法、语录、翻译模板、视频链接
```

---

## 贡献 / Contributing

欢迎 PR 增加新人物、语录或翻译模板，格式参考 `mentors.md` 已有结构。

---

## License

MIT
