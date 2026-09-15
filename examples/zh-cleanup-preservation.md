# Chinese cleanup preservation cases

Use these as acceptance constraints, not mandatory phrasings. For each applicable case, compare source and output; a fluent rewrite fails if it changes the protected meaning.

| Source or situation | Acceptance |
| --- | --- |
| 系統支援採集、儲存、展示。 | Keep all three capabilities explicit. 「從採集到展示」 is insufficient because storage is no longer explicit. Three items alone warrant no edit. |
| 這個方案成本低。然而，它不支援離線作業。 | Keep the contrast and the limitation. Do not replace 「然而」 with 「其實」 merely to sound conversational. |
| 當快取失效時，服務才會重新查詢資料庫。 | Keep the cache-expiry condition and 「才」; do not assert that the service always queries the database. |
| 對免費方案而言，每月上限是 100 次。 | Keep the free-plan scope and exact limit; do not generalize to all plans. |
| 段落先談方案 A 與 B，下一段說「聽起來比較省錢」。 | If the source does not identify which plan, flag ambiguity. Adding 「這」 alone does not resolve it; do not pick a plan. |
| 前段只談批次上傳；下一段說「聽起來很方便，但仍需手動重試」。 | If reference is unclear in context, naming 「批次上傳」 is an available repair. Preserve the manual-retry limitation. Do not change an already clear reference. |
| 留存率升到 72%。作者據此推測，產品可能已找到 PMF。 | Preserve the metric, attribution, inferential link, and uncertainty. Do not turn the author's inference into a confirmed PMF claim. |
| 第一步驗證簽章。第二步檢查期限。第三步核對權限。 | Preserve the ordered checks. Repeated syntax and numbering are functional, not defects. |
| 清理模式下，一句有冗語，相鄰句沒有問題。 | Change only the diagnosed span; do not replace valid neighboring wording to make the whole passage uniform. |
| 處理時間從兩小時降到四十分鐘。 | Preserve both values; 「效率大幅提升」 alone fails. Do not invent a cause or an additional percentage. |

A successful cleanup may leave the entire input unchanged. Assess whether the repair improves the identified problem, not how many patterns it removes.
