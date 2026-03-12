git-commit-for-ai-agents
========================

A specific context/skill to guardrail the process of committing changes
to a git repository executed by AI agents.

Installation
------------

If you use [Lola](https://github.com/mrbrandao/lola), this skill is part
of the `LeGambiArt` market.

```
lola market add LeGambiArt \
    https://raw.githubusercontent.com/LeGambiArt/lola-market/main/lola.yml
lola install git-commit-for-ai-agents
```

Or directly with
```
lola mod install https://github.com/jeffman/git-commit-for-ai-agents
```

If you are not using `Lola`, download the file to the proper directory
(the example uses `claude-code`):

```
curl \
    --create-dirs .claude/skills/git-commit-for-ai-agents \
    https://github.com/jeffman/git-commit-for-ai-agents/raw/refs/heads/main/SKILL.md
```

