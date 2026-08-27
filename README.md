# hermes-themes

Hermes Agent skins by the [friends-make-tools](https://github.com/friends-make-tools) friends.

## Themes

| Skin | Description | Source |
|---|---|---|
| `monokai-pro-spectrum` | Monokai Pro (Filter Spectrum) — charcoal `#222222`, orange `#fd9353`, yellow `#fce566` | VS Code theme, via [logicseed/monokai-pro-themes](https://github.com/logicseed/monokai-pro-themes) |
| `carbon-*` | IBM Carbon Design System palettes | [carbon-design-system/carbon](https://github.com/carbon-design-system/carbon) |

## Install

1. Copy the `.yaml` file to your skins folder:
   - Windows: `%LOCALAPPDATA%\hermes\profiles\<profile>\skins\`
   - Linux/macOS: `~/.hermes/skins/`
2. Activate it:

```bash
hermes config set display.skin <name>
```

Every surface (CLI, TUI, desktop) repaints live within about a second. Revert with `hermes config set display.skin default`.
