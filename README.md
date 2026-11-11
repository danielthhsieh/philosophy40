# 從馬克思到瑟爾

《哲學的 40 堂公開課》讀書會（2026-11-12）的動態簡報，涵蓋三個主題：

1. **馬克思**
2. **波普與孔恩**
3. **圖靈與瑟爾**

## 線上觀看

👉 https://danielthhsieh.github.io/philosophy40/

整份簡報是單一 HTML 檔，直接用瀏覽器開啟即可播放，不需要安裝任何東西。

## 操作方式

| 按鍵 | 動作 |
| --- | --- |
| `→`、`↓`、`Space`、`PageDown` | 下一頁 |
| `←`、`↑`、`PageUp` | 上一頁 |
| 輸入頁碼數字 | 跳到指定頁（`Backspace` 修改、`Esc` 取消） |

## 檔案結構

```
.
├── index.html   # 簡報本體（GitHub Pages 首頁）
├── photos/      # 人物照片：marx、popper、kuhn、turing、searle
└── .nojekyll    # 讓 GitHub Pages 直接發布靜態檔，不經過 Jekyll
```

## 更新方式

修改 `index.html` 後推送到 `main`，GitHub Pages 約一兩分鐘後就會自動更新：

```bash
git add -A
git commit -m "更新簡報"
git push origin main
```
