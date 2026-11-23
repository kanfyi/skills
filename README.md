# kan.fyi skills

Agent skills for [kan.fyi](https://kan.fyi), which hosts static sites: files in,
a live link out.

```bash
npx skills add kanfyi/skills
```

| Skill | What it teaches your agent |
|---|---|
| [`kan-publish`](skills/kan-publish/SKILL.md) | Publishing to kan.fyi: which door to use (the kan MCP tools or the HTTP API), shaping a payload that publishes, reading the five publish outcomes, and handling the access token safely. |

The skill expects a kan.fyi access token in `$KANFYI_PAT`. Mint one at
https://app.kan.fyi/settings/tokens. Docs: https://docs.kan.fyi.

## Issues and changes

This repository is a published copy. The skill is written and tested next to the
kan.fyi code it describes, and every change arrives here from there, so a pull
request here cannot be merged as is. Open an issue instead, or write to
security@kan.fyi for anything security-related.
