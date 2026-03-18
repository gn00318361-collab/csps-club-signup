# 青溪國小 114學年度第2學期 社團報名系統

線上社團報名網頁，學生填寫基本資料並選擇想報名的社團，報名資料自動寫入 Google Sheets。

## 功能

- 三步驟報名流程：填寫資料 → 選擇社團 → 確認送出
- 38 個社團分 6 大類（運動、舞蹈、藝術手作、益智學術、游泳、表演其他）
- 依年級自動篩選可報名的社團
- 報名資料即時寫入 Google Sheets
- 支援手機與電腦瀏覽

## 使用方式

開啟 `index.html` 即可使用，無需安裝任何套件。

## Google Sheets 串接

報名資料透過 Google Apps Script 寫入指定的 Google Sheets。如需更換試算表，請修改 `index.html` 中的 `GOOGLE_SCRIPT_URL`。
