# AI Skills Vault

A practical, reusable collection of AI skills for content creation, digital marketing, research, and AI-powered production.

This repository is designed to be:
- **Useful:** each skill gives an AI agent a repeatable workflow.
- **Editable:** customize the instructions for your own projects and voice.
- **Portable:** use the skills with Claude Code and adapt them for other compatible AI assistants.
- **Evidence-led:** prompts encourage fact-checking, clear assumptions, and honest reporting.

## What's inside

| Skill | What it helps with |
|---|---|
| `linkedin-content-creator` | Create useful, engaging LinkedIn posts and carousels |
| `seo-content-strategist` | Plan search-focused content and briefs |
| `social-media-strategist` | Build platform-aware social media plans |
| `ai-image-prompt-engineer` | Write detailed prompts for image-generation tools |
| `ai-video-producer` | Plan AI-assisted video projects from brief to edit |
| `marketing-research-analyst` | Research audiences, competitors, and market claims |
| `prompt-engineer` | Design, test, and improve reusable prompts |
| `claude-code-project-builder` | Plan and build software projects with Claude Code |

## Quick start

### Option A: Use with Claude Code in a project

1. Download or clone this repository.
2. Copy the `.claude/skills/` folder into the root of your own project.
3. Open that project in Claude Code.
4. Ask for a task that matches one of the skills, such as:  
   `Use the linkedin-content-creator skill to turn these notes into a LinkedIn post: ...`

Claude Code can discover project skills under `.claude/skills/`. Each skill lives in its own folder and has a `SKILL.md` file.

### Option B: Use a skill manually

Open the relevant `SKILL.md`, copy its instructions into your AI assistant, and provide the task brief and source material.

## Repository structure

```text
ai-skills-vault/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── .gitignore
└── .claude/
    └── skills/
        ├── linkedin-content-creator/SKILL.md
        ├── seo-content-strategist/SKILL.md
        ├── social-media-strategist/SKILL.md
        ├── ai-image-prompt-engineer/SKILL.md
        ├── ai-video-producer/SKILL.md
        ├── marketing-research-analyst/SKILL.md
        ├── prompt-engineer/SKILL.md
        └── claude-code-project-builder/SKILL.md
```

## How to get better results

For any skill, provide:
1. **Goal:** what outcome do you need?
2. **Audience:** who is it for?
3. **Context:** brand, product, platform, market, and constraints.
4. **Inputs:** source links, notes, data, assets, or examples.
5. **Output format:** post, brief, prompt, storyboard, code, or report.
6. **Success criteria:** what would make the result useful?

Do not ask an AI assistant to invent performance metrics, customer quotes, research findings, or credentials. Verify important claims and review generated work before publishing or deploying it.

## Customize this vault

- Add your own examples and preferred workflows.
- Put reference material in a skill's `references/` folder when needed.
- Add scripts or templates only when they genuinely support the workflow.
- Keep each skill focused on one clear job.
- Update the skill's `description` when its purpose changes.

## License

Released under the MIT License. See [LICENSE](LICENSE).
