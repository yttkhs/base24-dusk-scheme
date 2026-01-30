# Dusk

A [Base24](https://github.com/tinted-theming/base24) color scheme inspired by twilight - dark backgrounds with warm orange accents.

## Preview

| Color     | Hex       | Description                |
|-----------|-----------|----------------------------|
| base00    | `#1a1a1f` | Default Background         |
| base01    | `#252530` | Lighter Background         |
| base02    | `#3a3a45` | Selection Background       |
| base03    | `#5a5a65` | Comments                   |
| base04    | `#8a8a95` | Dark Foreground            |
| base05    | `#c5c5d0` | Default Foreground         |
| base06    | `#e0e0e8` | Light Foreground           |
| base07    | `#f5f5fa` | Lightest                   |
| base08    | `#e06c75` | Red - Errors               |
| base09    | `#ff9f43` | **Orange - Main Accent**   |
| base0A    | `#ffd866` | Yellow - Classes           |
| base0B    | `#98c379` | Green - Strings            |
| base0C    | `#56b6c2` | Cyan - Regex               |
| base0D    | `#61afef` | Blue - Functions           |
| base0E    | `#c678dd` | Purple - Keywords          |
| base0F    | `#be5046` | Brown - Deprecated         |
| base10    | `#141418` | Darker Background          |
| base11    | `#0e0e12` | Darkest Background         |
| base12    | `#ff8b8b` | Bright Red                 |
| base13    | `#ffb347` | **Bright Orange**          |
| base14    | `#b5e890` | Bright Green               |
| base15    | `#7fdbdb` | Bright Cyan                |
| base16    | `#7ec8f8` | Bright Blue                |
| base17    | `#d8a8f0` | Bright Purple              |

## Installation

### With tinty

Add to your `config.toml`:

```toml
[[items]]
name = "base24-dusk-scheme"
path = "https://github.com/yttkhs/base24-dusk-scheme"
themes-dir = "."
supported-systems = ["base24"]
```

Then run:

```bash
tinty install
tinty apply base24-dusk
```

## License

MIT
