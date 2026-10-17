# GaiaBit PM | BroadcastChannel Sync Edition

## 💡 為什麼之前不同步？
因為若沒有設定外部資料庫，不同 Google 帳號在瀏覽器內的 `LocalStorage` 是各自獨立的。
本次升級內建了 **BroadcastChannel API 與多層次同步機制**：
1. 當你用帳號 A 新增任務時，系統會立即廣播並同步至全站快取。
2. 同時支援 **JSON 匯出/匯入備份**，讓你在不同電腦或不同帳號間可以無痛移轉完整專案資料。
3. **嚴格白名單授權**：首位登入者為 Owner，可自由在後台設定授權哪些 Google Email 擁有後台編輯權限。
