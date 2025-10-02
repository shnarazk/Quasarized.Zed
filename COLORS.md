# Quasarized Color Reference

## Accent Colors

These are the primary accent colors used in syntax highlighting:

| Color   | Hex       | Usage |
|---------|-----------|-------|
| Yellow  | `#b58900` | namespace, label, constant, attribute, macro |
| Orange  | `#cb4b16` | class, type, struct |
| Red     | `#dc322f` | enum variant |
| Magenta | `#d33682` | type parameter |
| Violet  | `#6c71c4` | function |
| Blue    | `#268bd2` | operator, constructor, property |
| Cyan    | `#2aa198` | variable |
| Green   | `#859900` | keyword, special |

## Base Colors - Dark Theme

| Name    | Hex       | Description |
|---------|-----------|-------------|
| bg_4    | `#002b36` | Default Background (darkest) |
| bg_3    | `#073642` | Dark Foreground, Status bars, Selection |
| bg_3c   | `#421307` | Complement color (NEW) |
| bg_2    | `#30525c` | Medium Background (NEW) |
| bg_1    | `#586e75` | Light Background |
| bg_0    | `#657b83` | Comments, Line numbers |
| fg_0    | `#839496` | Lighter Foreground |
| fg_1    | `#93a1a1` | Default Foreground, Punctuation |
| fg_2    | `#c1c5bb` | Medium Foreground (NEW) |
| fg_3    | `#eee8d5` | Primary Text |
| fg_3c   | `#d4daee` | Complement color (NEW) |
| fg_4    | `#fdf6e3` | Brightest Foreground |

## Base Colors - Light Theme

Light theme uses the same colors but with fg and bg swapped:

| Name    | Hex       | Description |
|---------|-----------|-------------|
| fg_4    | `#002b36` | Primary Text (darkest) |
| fg_3    | `#073642` | Dark Text |
| fg_3c   | `#421307` | Complement color (NEW) |
| fg_2    | `#30525c` | Medium Text (NEW) |
| fg_1    | `#586e75` | Muted Text |
| fg_0    | `#657b83` | Comments, Line numbers |
| bg_0    | `#839496` | Lighter Background |
| bg_1    | `#93a1a1` | Medium Background |
| bg_2    | `#c1c5bb` | Light Background (NEW) |
| bg_3    | `#eee8d5` | Selection, Panel Background |
| bg_3c   | `#d4daee` | Complement color (NEW) |
| bg_4    | `#fdf6e3` | Default Background (brightest) |

## Key Differences from Solarized

Quasarized adds 4 new colors to the original Solarized palette:

1. **bg_2/fg_2** (`#30525c`) - A medium tone between base01 and base02
2. **bg_3c/fg_3c** (`#421307`) - Complement color of base02/Dark3
3. **c1c5bb** - A light tone for better gradients
4. **d4daee** - Complement color of base2/Light3

These additions provide more flexibility in UI design and better visual hierarchy.

## Syntax Highlighting Philosophy

- **Types are prominent** (Orange #cb4b16) - Easy to identify data structures
- **Functions stand out** (Violet #6c71c4) - Clear function calls
- **Variables are distinct** (Cyan #2aa198) - Track data flow
- **Keywords are subtle** (Green #859900) - Don't distract from code
- **Comments are muted** (bg/fg tones) - Present but not distracting
