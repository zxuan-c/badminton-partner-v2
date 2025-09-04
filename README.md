# 羽球雙打賽程播放器（GitHub Pages 版）

單檔前端工具，貼上清單就能逐場顯示、上一場/下一場切換，支援隨機打散與自動儲存。

## 使用方式（兩種）

### A. 直接用 GitHub Pages（推薦）
1. 建立一個新的 GitHub repository（例如 `badminton-fixture`）。
2. 把本資料夾的所有檔案上傳到 repo 的 **根目錄**（包含 `index.html`、`manifest.webmanifest`、`assets/icon-512.png`）。
3. 在 GitHub 專案頁面 → **Settings** → **Pages**：
   - **Source** 選擇 **Deploy from a branch**。
   - **Branch** 選擇 `main`（或 `master`）與根目錄 `/`，按 **Save**。
4. 幾十秒後會得到一個網址，例如：  
   `https://你的帳號.github.io/badminton-fixture/`  
   在 iPhone Safari 打開 → **分享** → **加入主畫面**，就像 App 一樣使用。

### B. 本地端直接開（離線）
- 直接用瀏覽器開啟 `index.html` 即可（建議用 Safari/Chrome）。
- 首次載入需網路（如果放在 GitHub Pages），之後頁面本身是純前端，能離線使用。

## 賽程格式
每行一場，格式：`A + B vs C + D`  
- 支援多重空格 / 全形空白，自動正規化。
- `vs` 大小寫與「對戰/對上/對」等詞會自動轉為 `vs`。
- 也接受 `+`、`、`、`，`、`,`、`＆`、`&` 作為分隔符。

## 快捷鍵
- `N` 下一場 / `P` 上一場 / `R` 重置到第 1 場 / `S` 隨機打散。

## iPhone 貼士
- Safari → 分享 → **加入主畫面**，會使用 `assets/icon-512.png` 做圖示。
- 已內建 `manifest.webmanifest` 與 Apple Touch Icon，體驗更像 App。

---

Made for Xuan 🏸
