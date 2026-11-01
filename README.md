<div align="center">

# ghostty-grok-theme

**A warm-amber near-black theme for [Ghostty](https://ghostty.org/).**

Inspired by the TUI aesthetics of Grok Build — near-black background (`#141414`) paired with an amber gold accent (`#D8B173`).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Ghostty](https://img.shields.io/badge/terminal-Ghostty-black?style=flat-square)](https://ghostty.org/)

[English](#palette-overview) | [中文说明](#中文说明)

</div>

---

## Palette Overview

| Role | Color | Hex |
| :--- | :--- | :--- |
| **Background** | Near Black | `#141414` |
| **Foreground** | Soft White | `#E1E1E1` |
| **Cursor** | Amber Gold | `#D8B173` |
| **Cursor Text** | Dark | `#141414` |
| **Selection Bg** | Charcoal | `#333333` |
| **Selection Fg** | Soft White | `#E1E1E1` |

### 16-Color ANSI Palette

```
  0 #1a1a1a    1 #c6787a    2 #a8b380    3 #d8b173
  4 #8fa7b6    5 #b592ab    6 #8bb8ae    7 #a8a8a8
  8 #505057    9 #e0a3a0   10 #c3cf9d   11 #e8c98e
 12 #a9c1cf   13 #cbaac3   14 #a8d2c8   15 #e1e1e1
```

---

## Installation

### Option 1: Theme file (recommended)

Download the theme into your Ghostty themes folder:

```bash
mkdir -p ~/.config/ghostty/themes && curl -fsSL https://raw.githubusercontent.com/lawrencewzen/ghostty-grok-theme/main/themes/Grok -o ~/.config/ghostty/themes/Grok
```

Then add this line to your `~/.config/ghostty/config`:

```ini
theme = Grok
```

Press `Cmd + Shift + ,` in Ghostty to reload.

### Option 2: Inline config

If you prefer not to use a separate theme file, append the color definitions directly into `~/.config/ghostty/config`:

```ini
# Grok Theme
palette = 0=#1a1a1a
palette = 1=#c6787a
palette = 2=#a8b380
palette = 3=#d8b173
palette = 4=#8fa7b6
palette = 5=#b592ab
palette = 6=#8bb8ae
palette = 7=#a8a8a8
palette = 8=#505057
palette = 9=#e0a3a0
palette = 10=#c3cf9d
palette = 11=#e8c98e
palette = 12=#a9c1cf
palette = 13=#cbaac3
palette = 14=#a8d2c8
palette = 15=#e1e1e1
background = #141414
foreground = #e1e1e1
cursor-color = #d8b173
cursor-text = #141414
selection-background = #333333
selection-foreground = #e1e1e1
```

---

<div id="中文说明"></div>

## 中文说明

基于 **Grok Build TUI** 风格的 [Ghostty](https://ghostty.org/) 配色主题：背景是近黑 `#141414`，光标和强调色用暖琥珀金 `#D8B173`，其余 ANSI 色均为低饱和柔和色调，长时间看不刺眼。

### 安装

```bash
mkdir -p ~/.config/ghostty/themes && curl -fsSL https://raw.githubusercontent.com/lawrencewzen/ghostty-grok-theme/main/themes/Grok -o ~/.config/ghostty/themes/Grok
```

在 `~/.config/ghostty/config` 中写入 `theme = Grok`，按 `Cmd + Shift + ,` 重载即可生效。也可以把上面 Option 2 的配色直接粘进 config。

---

## License

[MIT](LICENSE) © [Lawrence](https://github.com/lawrencewzen)
