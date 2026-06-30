# Claude Theme Hub

A small hub for Claude-inspired color themes across terminal, agent, and app
surfaces.

This repository links the individual theme repositories instead of vendoring
their files. Each project remains the source of truth for its own install
instructions, assets, and releases.

## Theme Repositories

| Target | Repository | Contains |
| --- | --- | --- |
| Otty terminal | [YuChenSSR/otty-claude-themes](https://github.com/YuChenSSR/otty-claude-themes) | Claude-inspired light and dark Otty terminal themes |
| Craft Agent | [YuChenSSR/claude-warm-craft-agent-theme](https://github.com/YuChenSSR/claude-warm-craft-agent-theme) | Claude Warm theme for Craft Agent |
| Codex App and Warp | [YuChenSSR/claude-warm-codex-app-theme](https://github.com/YuChenSSR/claude-warm-codex-app-theme) | Claude Warm Codex App themes plus matching Warp themes |

## Palette Family

The shared Claude Warm family keeps the same basic roles across apps:

| Role | Light | Dark |
| --- | --- | --- |
| Surface | `#f9f9f7` | `#2d2d2b` |
| Ink | `#2d2d2b` | `#f9f9f7` |
| Accent | `#cc7d5e` | `#cc7d5e` |
| Added | `#00c853` | `#00c853` |
| Removed | `#ff5f38` | `#ff5f38` |

## Use

Pick the app you want to theme, then follow that repository's README:

- Otty: terminal color theme files.
- Craft Agent: Claude Warm agent UI theme.
- Codex App: `codex-theme-v1` payloads and config installer.
- Warp: `.yaml` themes and soft background images.

## Add Another Claude Theme

Open a pull request that adds one row to the table above with:

- target app
- repository link
- short description of what the repo contains

Keep implementation files in the app-specific repository.

## Note

These themes are community-made and are not official Anthropic or Claude
assets.

## License

MIT. See [LICENSE](./LICENSE).
