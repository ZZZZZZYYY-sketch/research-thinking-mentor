# Research Thinking Mentor

A Chinese-first Agent Skill that trains independent scientific reasoning through paper reading, Socratic dialogue, research collaboration, literature novelty verification, experimental design, and paper argumentation.

## Modes

- `/mentor` — guided paper study with questions, hints and assessments.
- `/collab` — critical research collaboration, alternative models and novelty checks.
- `/hybrid` — automatic switching between mentor and collaborator (default).

## Install

```bash
git clone https://github.com/ZZZZZZYYY-sketch/research-thinking-mentor.git ~/.agents/skills/research-thinking-mentor
```

Restart or reload your agent as necessary, and verify that it discovers `SKILL.md`. Different Agent Skills hosts may interpret slash commands differently; you can also write `模式A`, `模式B`, or `双模式` in your prompt.

## Example

`/hybrid 请带我推导这篇近场信道估计论文的系统模型，然后检索相关工作并讨论真正未解决的建模问题。`

See [examples/usage.md](examples/usage.md) and the templates. The Skill depends on the host agent for web searches, PDF reading, and persistent storage; it cannot provide those tools by itself.
