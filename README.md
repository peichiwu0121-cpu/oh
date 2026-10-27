# 理財目標規劃工具

純靜態網站（PV / FV / PMT 理財目標分析），無需安裝、無需建置。

## 部署到 Cloudflare Pages（拖曳上傳）
1. Cloudflare Dashboard → Workers & Pages → Create → Pages → Upload assets。
2. 輸入專案名稱，將本資料夾（或 zip）直接拖進去，按 Deploy。

## 上傳到 GitHub（拖曳上傳）
1. 在 GitHub 建立新的 repository。
2. 點「uploading an existing file」，把本資料夾內的所有檔案拖進去，按 Commit changes。
3. 之後到 Cloudflare Pages 選「Connect to Git」，Build command 留空，Build output directory 留空（或填 `/`）。
