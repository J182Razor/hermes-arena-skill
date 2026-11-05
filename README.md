# arena-skill

Tournament of N sub-agents competing to produce the best answer. Portable Agent
Plugins v1 package (skills/ only, no MCP). Adapted from Jakeschincariol/arena-skill
(MIT) to use Hermes `delegate_task`.

## Install

`hermes plugins install /path/to/arena-skill --enable`

## Disclosure

- Spawns many sub-agent calls (cost scales with agent count; --quick uses 16).
- Writes only to `.arena/` in the current directory.
- Derived from Jakeschincariol/arena-skill (MIT).
