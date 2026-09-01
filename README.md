# 美容講師 × 醫美協作｜GitHub Pages 版

## 為什麼你之前上傳到 GitHub 沒有直接變網頁？

GitHub 的檔案頁面只會顯示 HTML 原始碼，不會把 repository 裡的 HTML 自動當網站執行。
要使用 **GitHub Pages**。

## 最快部署方式

1. 建立一個 GitHub repository。
2. 把這個資料夾內的 `index.html` 放在 repository 最上層。
3. GitHub repository → **Settings** → **Pages**。
4. `Build and deployment`：
   - Source：`Deploy from a branch`
   - Branch：`main`
   - Folder：`/(root)`
5. 按 Save。
6. 等待約 1～3 分鐘，GitHub Pages 會顯示網站網址。

網址通常會是：

`https://你的GitHub帳號.github.io/Repository名稱/`

## 這份 HTML 的特性

- 單一 `index.html`
- 不需要 npm
- 不需要 React
- 不使用 CDN
- 不需要圖片或其他 asset
- 手機／桌機響應式
- 可離線直接開啟
- 支援列印／另存 PDF
- 適合 GitHub Pages、Netlify、Cloudflare Pages 等純靜態網站

版本：2026-09-01
