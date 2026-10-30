# Mellow Café｜初版互動原型

純 HTML/CSS/JavaScript，無需安裝套件。

## 功能
- 首頁與資金／每日營運概況
- 花園自由佈置：購買家具、拖曳、旋轉、收納、座位統計
- 設備商店、固定菜單解鎖、自由配方研發
- 菜單售價、銷量、營收、成本、毛利與上下架
- 單品折扣／自訂組合優惠／多商品活動與宣傳單預覽
- 動物收容所、領養、寵物天地、活動區域選擇與照顧
- 庫存、安全庫存、自動補貨、手動補貨
- 員工與收支紀錄
- 瀏覽器 localStorage 存檔

## 部署到 GitHub Pages
1. 在 GitHub 建立 Public repository，例如 `mellow-cafe`。
2. 上傳 `index.html` 與 `README.md` 到 repository 根目錄。
3. 進入 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/(root)`，按 **Save**。
6. 等待部署完成，GitHub Pages 頁面會顯示網站網址。

## 原型限制
- 進度存在目前瀏覽器的 localStorage，不是雲端帳號存檔；清除網站資料可能會清除存檔。
- 營業採簡化模擬，尚未實作真正的顧客尋路、跨裝置同步、完整家具碰撞檢查及實際圖片素材。
