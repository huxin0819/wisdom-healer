# WisdomHealer 大佬心法疗愈

**当你迷茫、内耗、被否定、想翻盘……大佬们早就经历过了。**

把你的情绪状态告诉 AI，它会精准匹配最能疗愈你的大佬语录与视频切片。

---

## 快速开始 / Quickstart

### 方式一：直接粘贴给任意 AI（Claude / ChatGPT / Gemini 均可）

无需安装，把以下内容复制到对话开头，然后说出你的状态：

```
请阅读以下 Skill 指令，然后根据我的描述为我提供疗愈内容：

[将 SKILL.md 的全部内容粘贴在此]
[将 mentors.md 的全部内容粘贴在此]

我现在的状态是：[说出你的困境]
```

→ 直接复制 [SKILL.md](./SKILL.md) 和 [mentors.md](./mentors.md) 的内容即可使用。

---

### 方式二：Cursor 用户一键安装（自动触发）

```bash
git clone https://github.com/sisXin/wisdom-healer.git ~/.cursor/skills/wisdom-healer
```

重启 Cursor 后，**无需任何指令**，只要在对话中提到你的情绪或困境，Skill 会自动识别并触发疗愈流程。

---

### 方式三：Claude Project / ChatGPT Custom Instructions

把 `SKILL.md` 的内容粘贴进 Claude Project 的 **Project Instructions**，或 ChatGPT 的 **Custom Instructions**，之后每次对话都会自动带上疗愈能力。

**Claude Project 设置路径：** Projects → New Project → Instructions  
**ChatGPT Custom Instructions 路径：** Settings → Personalization → Custom Instructions

---

## 能解决什么 / What It Helps With

| 你现在的状态 | 会匹配到 |
|-------------|---------|
| 😵‍💫 迷茫 / 不知道方向 | Naval Ravikant, Steve Jobs, Yuval Harari |
| 😫 内耗 / 情绪低落 / 躺平 | Eckhart Tolle, Pema Chödrön, Naomi Osaka |
| 💔 感情受伤 / 关系问题 | Esther Perel, Taylor Swift, Drake |
| 😤 不自信 / 被否定 | Kanye West, Eileen Gu, Billie Eilish |
| 🚀 想突破 / 变强 / 翻盘 | Elon Musk, Oprah Winfrey, Sheryl Sandberg |
| 🧠 重大决策（跳槽 / 创业 / 分手） | Charlie Munger, Naval, Elon Musk |
| 😔 孤独 / 没人理解 | Drake, Billie Eilish, Michelle Obama |
| 🧩 身份冲突 / 打破标签 | Eileen Gu, Doja Cat, Emma Watson |
| 😵‍🔥 Burnout / 被压垮 / 想逃 | Simone Biles, Eckhart Tolle, Alysa Liu |
| 💹 加密 / Web3 / All-in 创业 | CZ 赵长鹏, 孙宇晨, 徐明星 Star |

还可以指定风格：
- 🌊 **想被安慰** → 温柔疗愈型（Tolle / Pema / Osaka）
- 🧊 **想被点醒** → 冷静理性型（Munger / Naval / Harari）
- 🔥 **想被激励** → 强势唤醒型（Kanye / Musk / Oprah）

---

## 输出示例 / Example Output

输入：*"最近开发了很多产品，大部分不能变现，很迷茫"*

```
━━━━━━━━━━━━━━━━━━━━━━━━━━
👤 Naval Ravikant | 天使投资人 / 硅谷智者

💬 经典语录：
"Desire is a contract you make with yourself to be unhappy until you get what you want."
—— 欲望是你与自己签订的一份合同：在得到你想要的之前，你将一直不快乐。

🎬 推荐视频：
• Joe Rogan Experience #1309 → youtube.com/watch?v=3qHkcs3kG44

✨ 为什么推荐给你：你问的问题本质是"我该做什么才不会白费力气"——
Naval 的框架就是为这个问题设计的。
━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 大佬名单 / Mentor Roster（19位）

Naval Ravikant · Steve Jobs · Yuval Noah Harari · Eckhart Tolle · Pema Chödrön · Naomi Osaka · Esther Perel · Taylor Swift · Drake · Kanye West · Eileen Gu · Billie Eilish · Elon Musk · Oprah Winfrey · Charlie Munger · Sheryl Sandberg · Michelle Obama · Simone Biles · Emma Watson · Doja Cat · Alysa Liu · **CZ 赵长鹏** · **孙宇晨** · **徐明星 Star**

---

## 文件结构 / File Structure

```
wisdom-healer/
├── SKILL.md       # 匹配逻辑 + 输出格式（AI 指令）
└── mentors.md     # 24 位大佬的语录、故事、视频链接数据库
```

---

## 贡献 / Contributing

欢迎 PR 补充新的大佬、语录或视频链接，格式参考 `mentors.md` 中已有结构。

---

## License

MIT
