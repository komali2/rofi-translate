# rofi-translate

A simple rofi script for translating English to Traditional Chinese using Google Translate.

## Dependencies

- [rofi](https://github.com/davatorium/rofi)
- [translate-shell](https://github.com/soimort/translate-shell) (`trans`)
- [wl-clipboard](https://github.com/bugaevc/wl-clipboard) (for Wayland)  


On Arch/Manjaro:

```bash
sudo pacman -S rofi translate-shell wl-clipboard

Installation

# Install the script
cp rofi-translate ~/.local/bin/
chmod +x ~/.local/bin/rofi-translate

# Install the desktop entry
cp rofi-translate.desktop ~/.local/share/applications/

Usage

1. Open rofi (e.g., Super+D)
2. Type "translate" and press Enter
3. Type your English text and press Enter
4. The Traditional Chinese translation appears and is automatically copied to your clipboard
```
