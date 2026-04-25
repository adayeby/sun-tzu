# sun-tzu (孙子)

---

An AI agent that gives strategic advice grounded in *The Art of War*. Not a philosophy chatbot — a strategist. Every response ends with something you can do or say.

## Author's note

I built this because I kept finding myself in situations — at work, at home, in relationships — where I wasn't sure what is the right thing to do and whether I did right or wrong. People sometimes blame themselves, sometimes blame others. Stress clouds judgment. Emotion picks the wrong battles. Sometimes even if I did the right thing, I couldn't get that confirmation anywhere. 

Sun Tzu cut through that for me. Not with motivation or platitudes, but with clarity. It affirms where I did right, surfaces blind spots I didn't know I had, and helps me understand why other people act the way they do. I started feeling calmer when facing tough situations and made more effective decisions, knowing that I have an intelligent ancient philosopher supporting me. 

I hope this agent can help you through your difficult situations too. 


## What it does

Invoke it when facing a tough situation: a conflict at work, a negotiation, a power dynamic, a competitive decision, or any moment where the wrong move costs you. It reads your situation through Sun Tzu's frameworks, maps it to a specific chapter and principle, and returns:

- **What to do** — concrete actions, ordered by priority
- **What to say** — exact phrases ready to use
- **What to watch out for** — the traps Sun Tzu warns against

## Installation

Download `sun-tzu.md` and place it in your `.claude/agents/` or `.copilot/agents/` directory.

## How to invoke

In Claude Code or Github Copilot CLI, tag the agent in your prompt. The example below is for Claude Code:

```
@sun-tzu <describe your situation>
```

## Files

| File | Description |
|---|---|
| `sun-tzu.md` | Agent definition — system prompt, frameworks, response format |
| `example-*.md` | Worked examples showing input and full response |

## Examples

See the `example-*.md` files for complete worked examples. Current examples:

- [`example-family-renovation-flooring.md`](example-family-renovation-flooring.md) — When to concede a mild preference to preserve relational capital in a multi-generational household

---

# 孙子

---

一个基于《孙子兵法》提供战略建议的agent。它不是一个哲学聊天机器人——而是一位战略家。每条回复都以你可以采取的行动或说出的话来结束。

## 作者手记

我总在工作、家庭、人际关系中陷入一些境地——不确定什么才是正确的做法，也不确定自己做对了还是做错了。人们有时责怪自己，有时责怪他人。压力会蒙蔽判断力，情绪会让人选错战场。有时即便我做对了，也无处获得肯定。

于是“孙子”出现了。它帮我打破了这种困境。不是通过励志或空洞的套话，而是通过清晰的洞察。它肯定我做得对的地方，揭示连我自己都未察觉的盲点，并帮我理解他人行为背后的原因。我发现处境艰难时，我可以不再让情绪淹没自己，真正尽力客观地看待情势，在这位古代智慧老人的帮助下做对的事。

我希望这个agent也能帮你渡过难关。

## 它能做什么

当你面临艰难处境时调用它：工作中的冲突、一场谈判、权力博弈、竞争性决策，或者难以分析风险的时刻。它会通过孙子的框架来审视你的处境，将其映射到特定的章节和原理，并返回：

- **该做什么** —— 具体行动，按优先级排序
- **该说什么** —— 可直接使用的原话
- **该警惕什么** —— 孙子温馨提示

## 安装

下载 `sun-tzu.md`，将其放入你的 `.claude/agents/` or `.copilot/agents/` 目录。

## 如何调用

在 Claude Code 或 Github Copilot CLI 中，在你的提示词中调用这个 agent：

```
@sun-tzu <描述你的处境>
```

## 文件

| 文件 | 描述 |
|---|---|
| `sun-tzu.md` | agent定义——系统提示词、框架、回复格式 |
| `example-*.md` | 展示输入和完整回复的示例 |

## 示例

完整的示例请查看 `example-*.md` 文件。目前包含的示例：

- [`example-family-renovation-flooring.md`](example-family-renovation-flooring.md) —— 家里老房子要装修了，我喜欢木地板可是别人都喜欢瓷砖，怎么办？
