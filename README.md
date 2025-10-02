# Quasalized.Zed

A modified color scheme extension for [Zed editor](https://github.com/zed-industries/zed) based on Solarized with 4 additional colors for better readability.

## Features

### Four more colors

**Quasalized** is a simple extension of the Solarized color scheme. It adds 4 colors to main tones for better readability and UI components.

- Dark4 `#002b36` was `base03` in Solarized
- Dark3 `#073642` was `base02` in Solarized
- Dark3c `#421307` **NEW** (complement color of Dark3)
- Dark2 `#30525c` **NEW**
- Dark1 `#586e75` was `base01` in Solarized
- Dark0 `#657b83` was `base00` in Solarized
- Light0 `#839496` was `base0` in Solarized
- Light1 `#93a1a1` was `base1` in Solarized
- Light2 `#c1c5bb` **NEW**
- Light3 `#eee8d5` was `base2` in Solarized
- Light3c `#d4daee` **NEW** (complement color of Light3)
- Light4 `#fdf6e3` was `base3` in Solarized

### Dark and light modes are completely symmetric

Flipping assigned colors in main tones gets the other mode. The color assignments are identical between modes.

### Color assignments for syntax highlighting

Types in Orange, Functions in Violet, and Variables in Cyan. The other elements are assigned to quiet colors. This suits strongly typed languages.

- Yellow `#b58900` - namespace, label, constant, attribute, macro
- Orange `#cb4b16` - class, type, struct
- Red `#dc322f` - enum variant
- Magenta `#d33682` - type parameter
- Violet `#6c71c4` - function
- Blue `#268bd2` - operator
- Cyan `#2aa198` - variable
- Green `#859900` - keyword, special

## Installation

1. Open Zed editor
2. Open the extensions view (Cmd+Shift+X on macOS, Ctrl+Shift+X on Linux/Windows)
3. Search for "Quasalized"
4. Click Install

Or install from source:
```bash
git clone https://github.com/shnarazk/Quasalized.Zed
cd Quasalized.Zed
# Follow Zed extension development instructions
```

## Usage

1. Open Zed settings (Cmd+, on macOS, Ctrl+, on Linux/Windows)
2. Select "Quasalized Dark" or "Quasalized Light" from the theme dropdown

## Credits

- Based on [Solarized](https://ethanschoonover.com/solarized/) by Ethan Schoonover
- Inspired by [Zed Legacy Themes](https://github.com/zed-extensions/legacy-themes)
- Adapted from [Quasarized for Helix](https://github.com/shnarazk/quasarized-for-helix)

## License

CC0 1.0 Universal - See LICENSE file for details