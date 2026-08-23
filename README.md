# 诗遇 · poetry-resonance

唐诗宋词共鸣 skill，为 WorkBuddy / CodeBuddy 等 agent 打造。以李白诗库为起点，把诗词和真实生活连起来。

## 功能

- **模式 A · 有感而发**：描述一段经历、场景或心情 → 匹配诗词 → 生成朋友圈 / 小红书文案
- **模式 B · 学习沉淀**：给一首诗 → 人话拆解创作背景与古今映射 → 输出学习笔记
- **模式 C · 今日日签**：结合节气 / 季节 / 日期推荐一首诗，附金句口令与寓意期盼

## 安装

```bash
git clone https://github.com/bonniegeng-max/poetry-resonance.git
cp -R poetry-resonance/poetry-resonance ~/.workbuddy/skills/
```

CodeBuddy 用户目标目录为 `~/.codebuddy/skills/`。

安装后在新会话中说"配首诗"、"拆解这首诗"或"今日一句"即可触发。

## 诗库

内置李白 27 首名篇结构化诗库（`references/poems.md`），每首含原文、人话背景、情绪内核、生活·工作共鸣场景、金句、配图意境、日签关联，持续扩充中。结构预留扩展其他诗人（杜甫、苏轼、王维……）。
