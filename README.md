# 三創互動樓層導覽（獨立測試版）

本專案與先前的 `syntrend-lookup` 分開，請建立新的 GitHub repository（例如 `syntrend-interactive`）部署。

## 功能
- B2、1F～12F 原始平面圖與透明可點擊櫃位區域
- 點選櫃位顯示名稱、櫃號及副牌／商品資訊
- 跨資料來源依專櫃名稱比對副牌
- 樓層切換、搜尋、縮放、手機瀏覽

## 上傳 GitHub Pages
將本資料夾內所有檔案（含 `maps`）上傳至新 repository 根目錄，Settings → Pages → Deploy from a branch → main / (root)。

## 重要限制
- 點擊區域為根據提供的平面圖人工建立的初版矩形熱區；不規則櫃位邊界、較小櫃位及部分重疊區域可能需要校正。
- 12F 展示與花園區域是功能區而非一般專櫃；10F/11F 非一般營業專櫃。
- 副牌以 Excel 專櫃名稱自動匹配，未配對資料不應解讀為沒有販售。
- 原始圖與資料在公開 GitHub Pages 上可被任何人存取，請先確認公開權限。
