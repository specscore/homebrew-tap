# SpecScore Homebrew Tap

Homebrew tap for [SpecScore](https://specscore.md) CLIs.

## Install

```bash
brew install specscore/tap/specscore
```

The first invocation auto-adds the tap and installs the CLI. To pin the tap separately:

```bash
brew tap specscore/tap
brew install specscore
```

## What's in the tap

| Formula | Description | Source |
|---|---|---|
| `specscore` | SpecScore CLI — lint, validate, and navigate Markdown specifications | [`specscore/specscore-cli`](https://github.com/specscore/specscore-cli) |

## How updates work

Formulae are published automatically by [GoReleaser](https://goreleaser.com/) on each tagged release of the upstream CLI. Manual edits to `Formula/*.rb` will be overwritten on the next release.

## License

MIT — see [LICENSE](LICENSE).
