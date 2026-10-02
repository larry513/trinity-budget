# Trinity's UofT Budget

Single-file offline budget app (HTML + localStorage). Open https://larry513.github.io/trinity-budget/

## v2 (2026-10-02)
- 水電帳單 Utility bills: separate bill types (Toronto Hydro, Enbridge, City of Toronto water & waste, internet) with editable billing cycles; multi-month bills spread into a monthly equivalent; set-aside per month, upcoming-bill reminders; $35 buffer covers overruns only.
- 取用存款 Use savings: withdraw from the savings jar (history, edit/delete, below-zero warning); in Excel, PDF, and the summary for Dad.
- 奶茶 Bubble tea quick entry: price per cup with recent-price chips, cups count, shop; average price per cup.
- 私房錢 Private stash + 我的總資產 My total money (hide/show amounts); kept out of all budgets and, by default, out of the summary for Dad and the PDF.

## v3 (2026-10-02)
- 合併匯入 Merge import (next to Replace import): every record has a stable id + updatedAt (old data migrated), deletions sync via tombstones, newest edit wins, preview (新增 / 更新 / 略過重複 / 刪除) before applying.
- 更多 → 搬資料・備份 Move data: bilingual how-to (export → WeChat / AirDrop / email → merge import); .json picker plus any-file fallback for iPhone Safari / Android Chrome; paste JSON still supported.
