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

## Reference project

A working MBTI quiz built with this toolkit lives at [gbs-toolkit/claude-gbs-mbti-demo](https://github.com/gbs-toolkit/claude-gbs-mbti-demo) — clone it, install this plugin, and you can rebuild the ROM end-to-end from Claude Code.

## License

MIT
