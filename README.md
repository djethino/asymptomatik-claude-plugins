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
| [asymptomatik-metacognition](https://github.com/djethino/claude-metacognition) | Metacognitive reflection and context preservation after compaction |
| [asymptomatik-cheatengine](https://github.com/djethino/claude-cheatengine) | Drive Cheat Engine (7.7+) from Claude Code: value scans, memory edits, pointers, watchpoints, code patches, Mono/IL2CPP (Unity) inspection, screenshots |

## Install a Plugin

```bash
/plugin install asymptomatik-souvenir@asymptomatik
/plugin install asymptomatik-metacognition@asymptomatik
```

After installing souvenir, run `/asymptomatik-souvenir:souvenir-init` to check the setup and build the first index.

After installing cheatengine (Windows, Cheat Engine 7.7 or later, Node.js 22.13 or later), run `/ce-install` once and restart Cheat Engine.

> The plugins were previously named `claude-souvenir` and `claude-metacognition`. Claude Code reserves the `claude-` prefix, so they were renamed: uninstall the old names and install the new ones. Souvenir keeps and migrates its index.

## License

MIT
