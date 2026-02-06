git-commit-for-ai-agents
========================

A specific context/skill to guardrail the process of committing changes
to a git repository executed by AI agents.

Installation
------------

If you use [Lola](https://github.com/mrbrandao/lola):

```
lola mod add https://github.com/rjeffman/git-commit-for-ai-agents
```

Or simply download the file to the proper directory (the example uses `claude`):

```
curl \
    --create-dirs .claude/skills/git-commit-for-ai-agents \
    https://github.com/jeffman/git-commit-for-ai-agents/raw/refs/heads/main/SKILL.md
```

