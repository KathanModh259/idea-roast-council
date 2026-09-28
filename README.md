# 🔥 Idea Roast Council

A Claude skill that roasts your idea before you waste six months building it.

Four roles, each locked to one job, argue about the same idea in a fixed order:

| Role | Job |
|---|---|
| **Believer** | Makes the strongest honest case FOR the idea |
| **Skeptic** | Tries to kill it if it deserves to die |
| **Investor** | Checks only one thing: does real money show up, and how fast |
| **Judge** | Rules last with one verdict: **BUILD**, **FIX FIRST**, or **KILL** |

Every ruling is saved (the biggest risk, the 10-minute test to run before writing code, and the change that flips FIX FIRST to BUILD), so when you come back, the council continues instead of starting over.

## Why not just ask "is my idea good?"

Because a plain chat hedges, flatters you, and lists ten generic pros and cons. Splitting the job into a believer, a skeptic, an investor, and a judge who *has* to pick a side is what forces a real answer.

## Install

**Claude.ai / Claude desktop:** download `idea-roast-council.skill` and upload it in the Skills section of Claude's settings.

**Claude Code:** copy the `idea-roast-council/` folder into `~/.claude/skills/` (or your project's `.claude/skills/`).

## Use

```
roast my idea: a WhatsApp bot that reminds small shop owners to follow up on unpaid credit
```

Also triggers on "run the council", "is this worth building?", or pasting back a previous council record to continue.

In Claude Code or Cowork, rulings are appended to `idea-council-log.md` in your working folder. In a regular chat, you get a record block to paste back next time.

## Credit

Based on "The Idea Roast Council" by [ORIGINAL CREATOR — add name and link]. Packaged as a Claude skill by [@KathanModh259](https://github.com/KathanModh259).
