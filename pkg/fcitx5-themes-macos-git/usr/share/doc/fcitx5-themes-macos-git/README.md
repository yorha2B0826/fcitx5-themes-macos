# Fcitx5 macOS Simple Themes

Simple, opaque, and macOS-style themes for Fcitx5. Designed for high visibility and clean aesthetics.

## Includes
- **MacOS-Simple**: Light theme with Apple Blue highlights.
- **MacOS-Dark**: Dark theme for night mode.

## Installation

### Manual
Copy the folders to your Fcitx5 themes directory:
```bash
mkdir -p ~/.local/share/fcitx5/themes/
cp -r MacOS-Simple MacOS-Dark ~/.local/share/fcitx5/themes/
```

### Configuration
Edit `~/.config/fcitx5/conf/classicui.conf`:
```ini
Theme=MacOS-Simple
DarkTheme=MacOS-Dark
UseDarkTheme=True
```

## License
MIT
