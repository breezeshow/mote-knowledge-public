# Mote Knowledge (public edition)

Public reference material about Mote, for people and agents writing or answering questions about it.

This repository is generated automatically from Mote's internal knowledge base.
**Do not edit it here**: every sync overwrites it. Send corrections to your Mote
contact or support@mote.com.

## Contents

`plugins/mote-knowledge/skills/mote-knowledge/SKILL.md` is the entry point: what Mote is, the rules
that apply to everything, and a map of the reference files under
`references/`. Everything is plain Markdown; no tooling is needed to read it.

## Use it with Claude Code

```
/plugin marketplace add breezeshow/mote-knowledge-public
/plugin install mote-knowledge@mote-knowledge-public
```

The `mote-knowledge` skill then loads automatically on Mote-related tasks.
