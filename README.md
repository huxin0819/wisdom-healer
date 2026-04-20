# WisdomHealer 大佬心法疗愈 🧠✨

> A Cursor Agent Skill that matches your emotional state to healing wisdom from world-class mentors — quotes, interviews, and video clips curated for real moments of doubt, burnout, and growth.

**当你迷茫、内耗、被否定、想翻盘……大佬们早就经历过了。**
这个 Skill 帮你在对的时机，找到对的一句话。

---

## 是什么 / What It Does

`WisdomHealer` 是一个 Cursor Agent Skill。当你跟 AI 聊到情绪困境时，它会自动：

1. **识别你的困境类型**（迷茫 / 内耗 / 感情 / 不自信 / Burnout / 重大决策……）
2. **精准匹配大佬**（Naval / Jobs / Munger / Tolle / Biles / Osaka……共 16+ 位）
3. **输出中英对照语录 + 真实视频切片链接**
4. **告诉你为什么这句话适合你现在**

---

## 涵盖困境 / Supported States

| 困境 | 推荐人物 |
|------|---------|
| 😵‍💫 迷茫 / 不知方向 | Naval Ravikant, Steve Jobs, Yuval Harari |
| 😫 内耗 / 情绪低落 | Eckhart Tolle, Pema Chödrön, Naomi Osaka |
| 💔 感情 / 关系问题 | Esther Perel, Taylor Swift, Drake |
| 😤 不自信 / 被否定 | Kanye West, Eileen Gu, Billie Eilish |
| 🚀 想突破 / 翻盘 | Elon Musk, Oprah Winfrey, Sheryl Sandberg |
| 🧠 重大决策 | Charlie Munger, Naval, Elon Musk |
| 😔 孤独 / 没人理解 | Drake, Billie Eilish, Michelle Obama |
| 🧩 身份冲突 / 打破标签 | Eileen Gu, Doja Cat, Emma Watson |
| 😵‍🔥 Burnout / 被压垮 | Simone Biles, Eckhart Tolle, Alysa Liu |

---

## 进阶匹配 / Style Filter

你还可以告诉 AI 你想要哪种风格：

- 🌊 **温柔疗愈** → Tolle / Pema / Osaka
- 🧊 **冷静理性** → Munger / Naval / Harari
- 🔥 **强势唤醒** → Kanye / Musk / Oprah

---

## 安装方式 / Installation

### 个人使用（Personal Skill）

```bash
# 克隆到 Cursor 个人 skills 目录
git clone https://github.com/sisXin/wisdom-healer.git ~/.cursor/skills/wisdom-healer
```

重启 Cursor 后即可生效。

### 项目使用（Project Skill）

```bash
# 克隆到项目的 .cursor/skills 目录
git clone https://github.com/sisXin/wisdom-healer.git .cursor/skills/wisdom-healer
```

---

## 使用方式 / How to Use

安装后，直接在 Cursor 对话框里说出你的状态即可：

> "我最近很迷茫，不知道下一步做什么"

> "有点 burnout，什么都不想干"

> "被否定了，很沮丧"

> "要做一个很难的决定，很纠结"

AI 会自动识别困境，匹配大佬，输出疗愈包。

---

## 文件结构 / File Structure

```
wisdom-healer/
├── SKILL.md       # 主指令：匹配逻辑 + 输出格式
└── mentors.md     # 数据库：16+ 位大佬的语录 + 视频链接
```

---

## 大佬名单 / Mentor Roster

Naval Ravikant · Steve Jobs · Yuval Noah Harari · Eckhart Tolle · Pema Chödrön · Naomi Osaka · Esther Perel · Taylor Swift · Drake · Kanye West · Eileen Gu · Billie Eilish · Elon Musk · Oprah Winfrey · Charlie Munger · Sheryl Sandberg · Michelle Obama · Simone Biles · Emma Watson · Doja Cat · Alysa Liu

---

## 贡献 / Contributing

欢迎 PR 补充新的大佬、语录或视频链接！
格式参考 `mentors.md` 中已有的结构。

---

## License

MIT
