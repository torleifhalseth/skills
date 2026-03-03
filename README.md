# Skills

A collection of [Agent Skills](https://agentskills.io) — folders of instructions, scripts, and resources that AI agents load dynamically to improve performance on specialized tasks.

## Skills

| Skill | Description |
| ----- | ----------- |
| [norwegian-writing](skills/norwegian-writing) | Norwegian language writing guidelines and best practices based on official rules from Språkrådet |

## Creating a New Skill

Create a folder under `skills/` with a `SKILL.md` file following the [Agent Skills specification](https://agentskills.io/specification):

```
skills/my-skill/
├── SKILL.md              # Required — frontmatter + instructions
├── scripts/              # Optional — executable code
├── references/           # Optional — additional docs (loaded on demand)
└── assets/               # Optional — templates, images, data files
```

```markdown
---
name: my-skill
description: A clear description of what this skill does and when to use it.
license: MIT
metadata:
  author: your-name
  version: "1.0"
---

# My Skill

[Instructions that the agent will follow when this skill is active]
```

## License

MIT
