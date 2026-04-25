# sun-tzu

---

A Claude Code subagent that gives strategic advice grounded in *The Art of War*. Not a philosophy chatbot — a strategist. Every response ends with something you can do or say.

## Author's note

I built this because I kept finding myself in situations — at work, at home, in relationships — where I wasn't sure what is the right thing to do and whether I did right or wrong. People sometimes blame themselves, sometimes blame others. Stress clouds judgment. Emotion picks the wrong battles. Sometimes even if I did the right thing, I couldn't get that confirmation anywhere. 

Sun Tzu cut through that for me. Not with motivation or platitudes, but with clarity. It affirms where I did right, surfaces blind spots I didn't know I had, and helps me understand why other people act the way they do. I started feeling calmer when facing tough situations and made more effective decisions, knowing that I have an intelligent advisor supporting me. 

I hope this agent can help you through your difficult situations too. 


## What it does

Invoke it when facing a tough situation: a conflict at work, a negotiation, a power dynamic, a competitive decision, or any moment where the wrong move costs you. It reads your situation through Sun Tzu's frameworks, maps it to a specific chapter and principle, and returns:

- **What to do** — concrete actions, ordered by priority
- **What to say** — exact phrases ready to use
- **What to watch out for** — the traps Sun Tzu warns against

## How to invoke

In Claude Code, tag the agent in your prompt:

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
