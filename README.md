# ASymptOmatik Claude Code Plugins

Plugin marketplace for Claude Code by ASymptOmatik.

## Installation

```bash
/plugin marketplace add djethino/asymptomatik-claude-plugins
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [asymptomatik-souvenir](https://github.com/djethino/claude-souvenir) | Memory across sessions: semantic and text search over past conversations and project files, file versioning |
| [asymptomatik-cheatengine](https://github.com/djethino/claude-cheatengine) | Drive Cheat Engine (7.7+) from Claude Code: value scans, memory edits, pointers, watchpoints, code patches, Mono/IL2CPP (Unity) inspection, screenshots |

## Install a Plugin

```bash
/plugin install asymptomatik-souvenir@asymptomatik
/plugin install asymptomatik-cheatengine@asymptomatik
```

After installing souvenir, run `/asymptomatik-souvenir:souvenir-init` to check the setup and build the first index.

After installing cheatengine (Windows, Cheat Engine 7.7 or later, Node.js 22.13 or later), run `/ce-install` once and restart Cheat Engine.

> Souvenir was previously named `claude-souvenir`. Claude Code reserves the `claude-` prefix, so it was renamed: uninstall the old name and install the new one. Souvenir keeps and migrates its index.

> `asymptomatik-metacognition` is retired: Claude Code's own progress (larger context, better compaction, memory) made it unnecessary. If you installed it, remove it with `/plugin uninstall asymptomatik-metacognition@asymptomatik`.

## License

MIT
