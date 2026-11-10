# Monthly maintenance · 每月維護

[Profile](README.md) · [繁體中文](#繁體中文)

Use this checklist for a monthly maintainer review and before a release.

- [ ] **Navigation:** open profile, README, installation and release links. Update moved destinations and remove unfinished placeholders.
- [ ] **Discoverability:** check each maintained repository's description and topics against its actual purpose. Clearly identify personal forks and preview projects.
- [ ] **Status:** distinguish planned, preview and released work. State the version, platform and date of any validation claim.
- [ ] **CI:** inspect failed and cancelled checks; identify the cause and track the specific fix. Rerun only checks relevant to that change.
- [ ] **Completion:** record each task's original objective, completed work and remaining conditions. A documentation publication, package build and successful runtime check are separate results.
- [ ] **Branches and tags:** before deleting a ref, confirm that no active task, release, installation or dependency still uses it. Preserve required history and restore information.
- [ ] **Release notes:** summarize user-visible changes, compatibility and known limits. Keep links to the applicable tests or verification results.
- [ ] **Research material:** review the publication boundary for examples, data and manuscripts; retain source attribution and existing license terms.

Keep a short dated record in the relevant project's issue, pull request or maintenance notes:

| Reviewed on | Repository / version | Verified result | Remaining work |
| --- | --- | --- | --- |
| YYYY-MM-DD | Project and ref | What was checked and its outcome | Concrete next action, or completed |

## 繁體中文

每月檢查一次，發布版本前也使用這份清單。

- [ ] **導覽連結：**開啟個人首頁、README、安裝及版本連結；更新已搬遷的目的地，移除未完成的占位文字。
- [ ] **分類與搜尋：**核對各維護中倉庫的描述和 topics 是否符合實際用途，清楚標示個人 fork 與預覽專案。
- [ ] **真實狀態：**區分規劃中、預覽與已發布內容；驗證聲明附上版本、平台及日期。
- [ ] **CI：**檢查失敗與取消的執行，定位原因並記錄具體修正；只重跑與該變更相關的檢查。
- [ ] **任務完成：**記錄每項任務的原始目標、已完成工作及剩餘條件。文件發布、套件建置與實際執行驗證分別記錄結果。
- [ ] **分支與標籤：**刪除 ref 前，確認沒有在途任務、版本發行、安裝或相依專案仍在使用；保留必要歷史與還原資訊。
- [ ] **版本說明：**說明使用者可見的變更、相容性及已知限制，附上適用的測試或驗證紀錄。
- [ ] **研究內容：**檢查示例、資料及稿件的公開範圍，保留來源註記與既有授權條款。

在相關專案的 issue、PR 或維護筆記中，簡短記錄檢查日期、倉庫／版本、
已驗證結果及剩餘工作。完成狀態應對應原始目標；有待處理條件時，寫明下一個具體動作。
