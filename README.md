# Paper Notebook Light

紙っぽいノート風のVS Codeライトテーマ

## コンセプト

白いディスプレイ感ではなく、**少し黄味がかった紙の上にインクで書いているような質感**のテーマです。

- 目にやさしいオフホワイト背景
- 濃すぎないインク色（ダークブラウン〜ダークグレー）
- コメントや無効コードは薄い鉛筆風グレー
- 「ノートに書いた読みやすい文字」をイメージ

## インストール

### ローカル開発版の使用

1. このリポジトリをクローン
2. VS Codeでフォルダを開く
3. `F5` を押して拡張開発ホストを起動
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
