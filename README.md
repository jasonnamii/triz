# triz

**TRIZ-based contradiction engine: resolve technical and strategic tradeoffs with 40 inventive principles.**

## Prerequisites

- **Claude Cowork or Claude Code** environment

## Goal

When two requirements conflict — improving A worsens B — you're stuck without a systematic way forward. triz structures the contradiction and applies proven invention principles to find non-obvious solutions. It combines 40 Inventive Principles, 4 Separation Principles, and Laws of System Evolution into a 5-stage pipeline.

## When & How to Use

Invoke when you face a true tradeoff that blocks progress. Best used when conventional approaches have failed. Input: conflicting requirements. Output: ranked solution directions mapped to TRIZ principles, plus system evolution forecasts.

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| Speed vs. quality | `"Ship 3x faster but quality metrics dropping"` | Technical contradiction→Inventive Principles→solutions ranked by cost/timeline |
| Cost vs. quality | `"Reduce costs 30% while maintaining premium spec"` | Separation principle→Inventive Principles→evolution forecast |
| Scale vs. customization | `"Platform for 100 customer needs without 100 implementations"` | Modularity + Universality→S-Curve forecasting |

## Key Features

- 5-stage pipeline: Define → Classify → Match → Generate → Verify
- 40 Inventive Principles with domain adapters
- 4 Separation Principles: Spatial, Temporal, Condition-based, Scale-based
- Laws of System Evolution for next-stage prediction
- Ideality scoring against ideal final result

## Works With

- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — contradiction resolution in creative jump phase
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — structures strategic contradictions
- **[trigger-dictionary](https://github.com/jasonnamii/trigger-dictionary)** — accessed as structured protocol

## Installation

```bash
git clone https://github.com/jasonnamii/triz.git ~/.claude/skills/triz
```

## Update

```bash
cd ~/.claude/skills/triz && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
