# Paper Notebook Light

A warm, paper-like light theme for VS Code with ink-style colors.

English | [日本語](README.ja.md)

## Concept

Instead of a bright white screen, this theme gives you the feeling of **writing with ink on slightly yellowed paper**.

- Eye-friendly off-white background
- Ink-style text colors (dark brown to dark gray, not too harsh)
- Pencil-gray comments and disabled code
- Designed to feel like "readable handwritten text in a notebook"

## Installation

### Method 1: Install from VSIX File (Recommended)

You can create and install a VSIX file even without a debug environment.

1. Clone this repository
   ```bash
   git clone https://github.com/kpab/vscode-paper-like-theme.git
   cd vscode-paper-like-theme
   ```

2. Package the VSIX file
   ```bash
   npm run package
   ```
   or
   ```bash
   npx @vscode/vsce package
   ```

3. Install in VS Code
   ```bash
   npm run install-extension
   ```
   or
   ```bash
   code --install-extension paper-notebook-light-0.0.1.vsix
   ```

4. Select the theme in VS Code
   - Press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`)
   - Select **Paper Notebook Light**

### Method 2: Development Host (F5 Debug)

1. Clone this repository
2. Open the folder in VS Code
3. Press `F5` or run **Extension** from the Run and Debug panel
4. In the development host, press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`) to select a theme
5. Select **Paper Notebook Light**

## Recommended Font Settings

For a more authentic notebook feel, add these font settings to your `settings.json`:

```json
{
  "editor.fontFamily": "'Iosevka', 'JetBrains Mono', 'Cascadia Code', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.lineHeight": 22,
  "editor.letterSpacing": 0.2,
  "editor.renderLineHighlight": "line",
  "editor.cursorBlinking": "smooth"
}
```

### Recommended Fonts

- **Iosevka** - Clean handwriting-inspired style with high readability
- **JetBrains Mono** - Modern and easy to read
- **Cascadia Code** - Beautiful coding font by Microsoft

> Note: Fonts must be installed on your system beforehand.

## Color Palette

- **Background**: `#F5F0E6` - Warm paper color
- **Foreground**: `#3A2E23` - Ink-style dark brown
- **Keywords**: `#854D2C` - Deep brown (bold)
- **Strings**: `#7A5136` - Brown tones
- **Comments**: `#9E9386` - Pencil-gray (italic)
- **Numbers**: `#A86434` - Orange-brown

## License

MIT
