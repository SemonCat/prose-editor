# Traditional Chinese for Taiwan

Apply for Traditional Chinese aimed at Taiwan. Preserve quotations, product names, platform terminology, and deliberate code-switching.

## Priorities

1. Preserve facts, stance, and genre.
2. Use natural Taiwan word order and terms.
3. Fix punctuation and translation artifacts.
4. Keep the author's formality and spoken texture.

## Contextual choices

- 視頻 → 影片／短影音
- 信息 → 資訊
- 軟件／硬件 → 軟體／硬體
- 網絡 → 網路
- 服務器 → 伺服器
- 屏幕／鼠標 → 螢幕／滑鼠
- 默認 → 預設
- 兼容 → 相容
- 反饋 → 回饋／意見
- 性價比 → CP 值
- 復盤 → 回顧／檢討；keep it when the team uses it
- 落地 → 執行／實作／真的做出來；keep it when established

Terms such as 平台、內容、流量、資料、優化, and 文檔 depend on context. Do not replace valid technical language mechanically. Mainland vocabulary in a Taiwan venue is a locale mismatch, not proof of AI authorship.

## Chinese calibration

Treat these as contextual candidates only when they cluster or obstruct meaning:

- 連詞跨句堆疊，例如反覆使用「以及／並且／同時／此外／因此／然而」；delete a connector when juxtaposition carries the relation.
- 雙音節或公文式填充，例如「進行討論／加以說明／予以處理／做出決定」；prefer the direct verb when it matches the author's register.
- Repeated 「不是……而是……」、forced parallel triples, or abstract nouns ending in 「性／感／化」; preserve real contrasts and established terminology.
- Adjacent sentences repeating the same clause order and explanatory tail; inspect whether the repeated syntax obscures relationships. Similar length alone is not a defect. Preserve parallel clauses and steps when their symmetry serves the reader.

Do not use punctuation density, comma or period counts, paragraph count, average paragraph length, or mean sentence length as general AI signals. The cited 2023 Simplified Chinese Q&A study and the community Lieflat corpus report do not establish targets for current Traditional Chinese writing. Lieflat's underlying corpus is unavailable for direct verification and its topics are not fully aligned; use its proposed patterns as editorial candidates, not validated thresholds.

Use full-width punctuation in Chinese sentences. Keep URLs, code, identifiers, full English sentences, digits, and units half-width. Prefer 「」 then 『』. Follow the author's Chinese-English spacing. Preserve existing particles and humor; do not add them to simulate personality. Formal Taiwan prose is still natural prose.

## Reference and clause checks

- **Unclear paragraph-opening reference:** Identify the object of 「聽起來……」「問題在於……」 before changing it. When the source identifies the object but the opening is ambiguous, name that object; use 「這」 only with a unique antecedent. Keep clear implicit references, quotations, and dialogue. If the source leaves multiple plausible objects, flag the ambiguity instead of choosing one.
- **Overloaded pre-noun modifiers:** Move a modifier into a following clause only when the reader must backtrack to find the head noun. Preserve which object each restriction modifies; use no character-count cutoff.
- **Duplicated topic frame:** Fold 「對……而言／在……方面」 into the subject only when the scope survives. Keep frames that distinguish populations, perspectives, or conditions.
- **Restatement wrappers:** Inspect 「這意味著／這表明／換句話說」 for actual repetition. Merge only equivalent content; retain inference, qualification, or explanation that adds a distinct claim. Do not convert a conclusion into an observed fact.
- **Logical connectors:** Preserve contrast, causality, concession, and temporal conditions. 「然而」 and 「其實」 are not interchangeable; deleting 「當……時」 must not turn a conditional claim into an unconditional one.

For Chinese cleanup, check the [preservation cases](../examples/zh-cleanup-preservation.md) before delivery.
