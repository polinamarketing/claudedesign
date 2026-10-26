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

## Logo Design Skill

[Logo Design Skill](https://github.com/kaankiziltug/logo-design-skill) (MIT, by kaankiziltug) helps you design logos and brand marks. It covers the brief, concepts, SVG construction, testing (16 px, one-colour, shelf test), presentation boards and brand guidelines. It includes a searchable reference library of more than 1,400 real-world SVG logos. Those logos are trademarks of their owners and are there only for study. See `TRADEMARKS.md` in the skill folder.

- `.claude/skills/logo-design/`: the skill. Claude Code picks it up automatically in this repo. Ask for a logo, or run `/logo-design`. Its scripts are plain Python 3 with no dependencies.
- `dist/logo-design/logo-design.zip`: the full skill for upload to claude.ai under **Settings → Capabilities → Skills**. If the upload is too large, use `logo-design-lite.zip`, which leaves out the SVG library and its gallery.

To install it in your local Claude Code, run `/plugin marketplace add kaankiziltug/logo-design-skill`, then `/plugin install logo-design@logo-design-skill`.
