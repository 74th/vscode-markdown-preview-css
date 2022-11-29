# VS Code でマークダウンプレビューを見やすくするための CSS

Repository: https://github.com/74th/vscode-markdown-preview-css

## つかい方

設定 `"markdown.styles"` に設定します。

```json
{
  "markdown.styles": [
    "https://74th.github.io/vscode-markdown-preview-css/css/header-underline.css",
    "https://74th.github.io/vscode-markdown-preview-css/css/visible-background.css"
  ]
}
```

## CSS

- ヘッダーに下線を追加して見やすくする [https://74th.github.io/vscode-markdown-preview-css/css/header-underline.css](css/header-underline.css)
- バックグラウンドを灰色にして、透過画像が、ダークテーマ、ライトテーマでも見えるようにする [https://74th.github.io/vscode-markdown-preview-css/css/visible-background.css](css/visible-background.css)
