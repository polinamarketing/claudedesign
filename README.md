# claudedesign

## Impeccable design skill

[Impeccable](https://impeccable.style) (v4.5.2, Apache-2.0, from [pbakaus/impeccable](https://github.com/pbakaus/impeccable)) is installed here:

- `.claude/skills/impeccable/`: the skill. Claude Code picks it up automatically in this repo. Run `/impeccable init`, then commands such as `/impeccable polish`, `/impeccable audit` or `/impeccable critique`.
- `.claude/agents/impeccable-*.md`: its helper subagents.
- `dist/impeccable-skill.zip`: the same skill packaged for upload to claude.ai (Claude, Claude Design, Claude Desktop) under **Settings → Capabilities → Skills → Upload skill**.

To install it in your local Claude Code for all projects, run `/plugin marketplace add pbakaus/impeccable` and then install Impeccable from `/plugin`. You can also run `npx impeccable install --providers=claude --scope=global`.

## Taste Skill

[Taste Skill](https://github.com/leonxlnx/taste-skill) (MIT, by Leonxlnx) is an anti-slop frontend skill set. The `.claude/skills/` folder holds 12 of its skills, each named by its install name. The main one is `design-taste-frontend` (v2). The others are `gpt-taste`, `redesign-existing-projects`, `high-end-visual-design`, `minimalist-ui`, `industrial-brutalist-ui`, `full-output-enforcement`, `image-to-code`, `stitch-design-taste`, `brandkit`, `imagegen-frontend-web` and `imagegen-frontend-mobile`. The legacy v1 is not included.

Zips for claude.ai are in `dist/taste-skill/`, one per skill. Upload each skill you want separately under **Settings → Capabilities → Skills**.

To install it in your local Claude Code, run `/plugin marketplace add Leonxlnx/taste-skill`, then `/plugin install taste-skill@taste-skill`.
