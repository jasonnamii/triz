# TRIZ

**TRIZ-based contradiction solving engine with 40 inventive principles.**

When two requirements conflict (improving A worsens B), this skill structures the contradiction and applies the 40 Inventive Principles, 4 Separation Principles, and Laws of System Evolution to generate solutions.

### Example Prompts

```
"We need it cheaper but higher quality" → identify contradiction→match principles→generate solutions→evaluate vs Ideal Final Result
"Solve this tradeoff: speed vs accuracy" → technical contradiction→matrix→top principles→solutions
```

### Pipeline

1. **Define** — Contradiction in one sentence
2. **Classify** — Technical (parameter conflict) or Physical (same attribute, opposite needs)
3. **Match** — Technical → 40 Principles + Matrix; Physical → 4 Separation Principles
4. **Generate** — Apply matched principles to the problem
5. **Verify** — Evaluate against Ideal Final Result

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

This is one of 25 custom skills. See the full catalog: [https://github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
