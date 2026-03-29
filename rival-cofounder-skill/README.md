# Rival Cofounder Skill

`rival-cofounder` 是一个给 Codex 用的 Skill。  
它不是来夸你想法好的，而是像一个**会顶嘴但靠谱的联合创始人**，专门帮你：

- 挑产品想法里的漏洞
- 砍掉过大的 MVP
- 把模糊概念压成清晰定位
- 逼你讲明白用户、痛点、价值和下一步

## 核心一句话

不是陪你自我感动。  
是帮你把烂想法打磨成能做、能讲、能卖的方向。

## 适合什么场景

- 你有个产品想法，但总觉得虚
- 你想让 AI 当“劲敌型合伙人”
- 你需要别人帮你收 MVP
- 你想测试一个项目到底值不值得做
- 你想把 landing page / launch idea / demo 概念讲清楚

## 不适合什么场景

- 单纯需要安慰
- 纯情绪陪伴
- 代码调试
- 已经确定方向，只想润色文案

## Skill 结构

```text
rival-cofounder-skill/
  README.md
  rival-cofounder/
    SKILL.md
    agents/
      openai.yaml
    references/
      examples.md
```

## 这个 Skill 会怎么工作

默认会按这个顺序拆你的想法：

1. 真问题是什么
2. 目标用户是不是太宽
3. 产品描述里哪些词是空话
4. MVP 哪些部分该砍
5. 为什么别人现在就该在意
6. 下一步到底该做什么

## 默认输出结构

- `Brutal Truth`
  - 最核心的问题
- `What Actually Works`
  - 真正值得保留的部分
- `What To Cut`
  - 该砍掉的东西
- `Sharper Version`
  - 更锋利的产品重写版
- `Next Move`
  - 现在最该做的一步

## 示例触发词

- “狠狠挑毛病，别顺着我说。”
- “把这个想法砍成一个真实 MVP。”
- “像联合创始人一样顶我。”
- “告诉我这个产品到底值不值得做。”

## 发布价值

这个仓库适合放到 GitHub 上，原因很简单：

- 概念清晰
- 有性格
- 和一堆普通提示词不一样
- 能直接展示你对产品思考和 AI 交互风格的理解
