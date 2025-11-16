# Paper Notebook Light

紙っぽいノート風のVS Codeライトテーマ

[English](README.md) | 日本語

## コンセプト

白いディスプレイ感ではなく、**少し黄味がかった紙の上にインクで書いているような質感**のテーマです。

- 目にやさしいオフホワイト背景
- 濃すぎないインク色（ダークブラウン〜ダークグレー）
- コメントや無効コードは薄い鉛筆風グレー
- 「ノートに書いた読みやすい文字」をイメージ

## インストール

### 方法1: VSIXファイルからインストール（推奨）

デバッグ環境がなくても、VSIXファイルを作成してインストールできます。

1. このリポジトリをクローン
   ```bash
   git clone https://github.com/kpab/vscode-paper-like-theme.git
   cd vscode-paper-like-theme
   ```

2. VSIXファイルをパッケージ化
   ```bash
   npm run package
   ```
   または
   ```bash
   npx @vscode/vsce package
   ```

3. VS Codeにインストール
   ```bash
   npm run install-extension
   ```
   または
   ```bash
   code --install-extension paper-notebook-light-0.0.1.vsix
   ```

4. VS Codeでテーマを選択
   - `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`) を押す
   - **Paper Notebook Light** を選択

### 方法2: 開発ホストで使用（F5デバッグ）

1. このリポジトリをクローン
2. VS Codeでフォルダを開く
3. `F5` を押すか、Run and Debug パネルから **Extension** を実行
4. 開発ホスト側で `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`) を押してテーマ選択
5. **Paper Notebook Light** を選択

## 推奨フォント設定

テーマと合わせて、以下のフォント設定を `settings.json` に追加すると、より紙ノート風の雰囲気になります。

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

### 推奨フォント例

- **Iosevka** - 整った手書き風・可読性高い
- **JetBrains Mono** - モダンで読みやすい
- **Cascadia Code** - Microsoftの美しいコーディングフォント

> 注：フォントは事前にシステムにインストールしておく必要があります。

## カラーパレット

- **背景色**: `#F5F0E6` - 温かみのある紙色
- **前景色**: `#3A2E23` - インク風のダークブラウン
- **キーワード**: `#854D2C` - 濃いブラウン（太字）
- **文字列**: `#7A5136` - ブラウン系
- **コメント**: `#9E9386` - 鉛筆風グレー（イタリック）
- **数値**: `#A86434` - オレンジブラウン

## ライセンス

MIT
