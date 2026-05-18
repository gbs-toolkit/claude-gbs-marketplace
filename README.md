# claude-gbs-marketplace

A Claude Code plugin marketplace that ships the [`gbs`](https://github.com/gbs-toolkit/claude-gbs-plugin) plugin — a GB Studio 4.x toolkit (structured MCP tools + skills) for assisting Game Boy game development from Claude Code.

## Install

In any Claude Code session:

```
/plugin marketplace add https://github.com/gbs-toolkit/claude-gbs-marketplace
/plugin install gbs@gbs-toolkit
```

`/plugin list` should now show `gbs` as installed.

## What's in the box

| Plugin | Description | Repo |
|---|---|---|
| `gbs` | GB Studio 4.x MCP tools + skills | [gbs-toolkit/claude-gbs-plugin](https://github.com/gbs-toolkit/claude-gbs-plugin) |

The plugin itself depends on the [`@gbs-toolkit/mcp-server`](https://www.npmjs.com/package/@gbs-toolkit/mcp-server) npm package, launched on demand via `npx`.

## Reference projects

Four demos illustrate different facets of the plugin. Clone any of them, install this plugin, configure `.mcp.json`, and Claude Code drives the build end-to-end:

| Repo | Genre | Highlights |
|---|---|---|
| [`claude-gbs-mbti-demo`](https://github.com/gbs-toolkit/claude-gbs-mbti-demo) | MBTI personality quiz | Working ROM today — variable-driven scoring across 20 questions, 16 result types |
| [`claude-gbs-rpg-demo`](https://github.com/gbs-toolkit/claude-gbs-rpg-demo) | Top-down RPG | NPC dialogue, inventory variables, simple combat (skeleton — Claude fills resources) |
| [`claude-gbs-platformer-demo`](https://github.com/gbs-toolkit/claude-gbs-platformer-demo) | Side-scrolling platformer | Jump physics, coin pickup, enemy collision, goal flag (skeleton) |
| [`claude-gbs-maga-demo`](https://github.com/gbs-toolkit/claude-gbs-maga-demo) | Satirical text-adventure | Real-photo → DMG sprite via `convert_image_to_sprite`; branching dialogue (skeleton) |

## License

MIT
