# Paper Notebook Light

A warm, paper-like light theme for VS Code with ink-style colors.

English | [日本語](README.ja.md)

## Concept

Instead of a bright white screen, this theme gives you the feeling of **writing with ink on slightly yellowed paper**.

- Eye-friendly off-white background — no harsh pure white
- Ink-style syntax colors: brown ink for keywords, faded green and blue ink accents for strings and types
- Soft pencil-toned comments and line numbers, tuned for readability
- The entire workbench — terminal, sidebar, widgets, menus — stays in paper tones

## Screenshots

<!-- TODO: Add screenshots before publishing. Suggested shots:
  images/overview.png   — full editor with sidebar + terminal open
  images/typescript.png — TypeScript code sample
  images/markdown.png   — Markdown editing

![Overview](images/overview.png)
![TypeScript](images/typescript.png)
![Markdown](images/markdown.png)
-->

*Screenshots coming soon.*

## Usage

Install from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=kpab.paper-notebook-light) (or run `ext install kpab.paper-notebook-light` from Quick Open — `Ctrl+P` / `Cmd+P`), then:

1. Press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`)
2. Select **Paper Notebook Light**

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

| Element | Color | Description |
| --- | --- | --- |
| Background | `#F5F0E6` | Warm paper color |
| Foreground | `#3A2E23` | Ink-style dark brown |
| Keywords | `#854D2C` | Deep brown (bold) |
| Strings | `#5C6E4E` | Muted green ink |
| Types | `#4E5F73` | Faded blue ink |
| Functions | `#6C3F2C` | Dark roasted brown |
| Numbers | `#A86434` | Orange-brown |
| Comments | `#8A7D6D` | Soft pencil gray (italic) |

## Development

Want to try local changes or build the extension yourself?

1. Clone this repository
   ```bash
   git clone https://github.com/kpab/vscode-paper-like-theme.git
   cd vscode-paper-like-theme
   ```

2. Try it in the Extension Development Host: open the folder in VS Code, press `F5`, then pick the theme with `Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`

3. Or package and install a VSIX:
   ```bash
   npm run package
   npm run install-extension
   ```

## License

MIT
