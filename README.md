# GaiaBit 毛焦點 | 專業專案管理與戰略儀表板

本專案為 **GaiaBit 毛焦點**（收容動物遠端觀看與互動平台）之專屬戰略導覽與每日行程管家系統。

## 🏛️ 視覺與設計風格
採用國立臺北教育大學（NTUE）官網之沉穩深藍 (`#0A2540`)、質感灰白與精準排版，展現高專業度與可信賴感。

## 🔐 嚴格權限控管機制 (Admin vs. Public)
- **一般訪客**：進入網站僅能瀏覽宏觀戰略、雙週衝刺任務與專業企劃書（唯讀模式，無法新增或刪除）。
- **管理者登入**：透過 Supabase Auth 身分驗證。登入後即時解鎖 `admin-panel` 編輯與刪除任務權限。

## 🚀 三步快速部署
1. **GitHub**：將本專案 (`index.html`, `README.md`, `vercel.json`) 上傳至您的 GitHub 儲存庫。
2. **Vercel**：登入 Vercel 連結該 GitHub 專案，點選 Deploy 即可自動部署上線。
3. **Supabase**：於 Supabase 建立 `schedules` 資料表並設定 RLS 策略，將 URL 與 Key 填入 `index.html` 中即可。
