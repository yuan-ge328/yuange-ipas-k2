源格 YuanGe｜科目二全真衝刺教室 V1.0
===================================
版本日期：2026-10-29

一、適用範圍
iPAS AI 應用規劃師中級／科目二：大數據處理分析與應用
來源：115年第一次能力鑑定（2026/05/23）官方公告試題，共50題。
第1～38題一般選擇題，第39～50題程式題。標準答案沿用公告答案。
此網站不是官方系統；AI 解題提示不是官方解析。

二、模考規格
- 50題單選；90分鐘倒數，時間到自動交卷。
- 模擬滿分100分，每題2分；70分（35題）為達標門檻。
- 模考不顯示答案；交卷後才顯示標準答案、AI簡易解析、主題表現。
- 可跳題、返回修改、標記疑問題目。
- 中途關閉後再開啟，可接續尚未交卷的測驗；計時不暫停。
- 首批只使用官方115年第1次考題，不會自動重生新的官方考題。

三、Windows 本機預覽
1. 將 ZIP 解壓縮到同一個資料夾。
2. 雙擊 index.html（建議 Chrome/Edge）；有些瀏覽器對 file:// 的儲存功能有限制。
3. 若要完整測試離線安裝功能，請部署到 HTTPS GitHub Pages。

四、GitHub Pages 第一次發布（全新獨立儲存庫）
1. 登入 https://github.com/ → 右上角 + → New repository。
2. 儲存庫名稱建議 yuange-ipas-k2；Visibility 選 Public，按 Create repository。
3. 進入 Code → Add file → Upload files，將本 ZIP 中的「網站檔案」上傳至儲存庫根目錄。
   注意：assets/ 和 reference/ 是資料夾，必須保留其目錄結構；最簡單方式是
   先在電腦解壓縮，將整個網站內容（包括資料夾）拖曳到上傳區，不要只上傳 ZIP。
4. 按 Commit changes。
5. Settings → Pages → Build and deployment → Source: Deploy from a branch；
   Branch: main；Folder: /(root) → Save。
6. 網站連結：https://<你的GitHub帳號>.github.io/yuange-ipas-k2/
   （如果自訂儲存庫名稱，網址也會跟著改。）
7. 更新時只要再次上傳有變更的檔案並提交，不需重新設定 Pages。

五、iPhone/Android 使用
1. 先用 Safari / Chrome 連線造訪 GitHub Pages 網址。
2. iPhone：分享 → 加入主畫面；Android：瀏覽器選單 → 安裝或加入主畫面。
3. 首次完整連線載入、等待資源快取後，才進行飛航模式測試。
4. 學習紀錄存在本機瀏覽器儲存空間。更新或刪除主畫面捷徑前，先到「設定」匯出 JSON 備份。
5. 不要把不同瀏覽器、不同主畫面 App 的進度視為自動同步。

六、正確性與限制
- 系統檢核：原題號1～50、標準答案50筆、A～D選項及官方原卷圖像逐題保留。
- PDF的部分數學式、圖表與程式片段以圖像顯示（特別是第49題四組程式碼選項）。
- 文字版本由 PDF 擷取，若與圖像存在排版差異，以題內「官方原卷」及隨附 PDF 為準。
- 50題均附 AI 編寫的簡要解題方向，尚未逐題經外部專家覆核。
- 個別官方題目的技術敘述也可能過度簡化，系統不自行改動標準答案。
- 使用者的錯題、作答記錄不會自動傳到伺服器，也不會呼叫付費 AI API。

七、網站檔案
index.html - 網站首頁
style.css - 版面
app.js - 作答、計時、評分、備份邏輯
questions.js - 官方題目及答案，另含非官方 AI 短解析
assets/ - 所有題目公式/圖表/原卷圖像（離線快取使用）
reference/official-115-k2.pdf - 原始官方公告 PDF
icon-192.png、icon-512.png - 桌面圖示
manifest.webmanifest、sw.js - 安裝與離線快取
115年官方50題核對表.csv - 方便核對答案與來源

提醒：考試公告和補充規定若更新，以 iPAS 官網及當年度正式簡章為準。
