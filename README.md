# claudedesign

## Impeccable design skill

[Impeccable](https://impeccable.style) (v4.5.2, Apache-2.0, from [pbakaus/impeccable](https://github.com/pbakaus/impeccable)) is installed here:

- `.claude/skills/impeccable/`: the skill. Claude Code picks it up automatically in this repo. Run `/impeccable init`, then commands such as `/impeccable polish`, `/impeccable audit` or `/impeccable critique`.
- `.claude/agents/impeccable-*.md`: its helper subagents.
- `dist/impeccable-skill.zip`: the same skill packaged for upload to claude.ai (Claude, Claude Design, Claude Desktop) under **Settings → Capabilities → Skills → Upload skill**.

To install it in your local Claude Code for all projects, run `/plugin marketplace add pbakaus/impeccable` and then install Impeccable from `/plugin`. You can also run `npx impeccable install --providers=claude --scope=global`.
