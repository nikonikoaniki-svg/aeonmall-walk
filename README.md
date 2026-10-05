# イオンモールウォーキング制覇（近畿版） V26

## 修正
- モール詳細画面が開かなかった不具合を修正
- 原因: 旧1枚写真用の `photoPreview` 参照が残っていた
- 2枚写真用 `photoExteriorPreview` / `photoCoursePreview` に完全移行
- JavaScript構文チェック済み
