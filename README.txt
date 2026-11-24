Rest Time PWA

檔案：
  index.html / manifest.webmanifest / sw.js / icons/

部署到 GitHub Pages：
  1. 在 GitHub 建立新的 repository（Public）
  2. 把整個資料夾的內容（不是資料夾本身）上傳到 repository 根目錄
  3. Settings → Pages → Source 選 Deploy from a branch，Branch 選 main / (root)，Save
  4. 幾分鐘後可用 https://帳號.github.io/repo名稱/ 開啟

安裝：
  Android Chrome：選單 → 安裝應用程式
  iPhone Safari：分享 → 加入主畫面

更新：
  修改 index.html 後重新上傳。有網路時開啟 App 即會取得最新版（可能需重開一次）。
  若更改了圖示或檔案清單，請同時把 sw.js 的 CACHE 版本號加一。
