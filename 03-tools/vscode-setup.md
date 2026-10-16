# VS Code 基礎建置與環境設定

記錄新電腦或重新安裝 VS Code 時必要的設定步驟。

## 1. 視覺與字型設定
- **字型**：安裝並設定 `Fira Code`，開啟 `editor.fontLigatures: true` 啟用連字功能。
- **佈景主題**：使用 `Catppuccin for VSCode` 的 `Catppuccin Mocha`。

## 2. 核心設定 (settings.json 摘要)
```json
{
  "files.autoSave": "afterDelay",
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.formatOnSave": true,
  "editor.unicodeHighlight.nonBasicASCII": false
}
```
## 3. 核心必裝外掛
- **Prettier**：自動排版
- **Material Icon Theme**：檔案圖示美化
- **GitLens**：版控輔助