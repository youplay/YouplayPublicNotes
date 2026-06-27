# Youplay Public Notes

以 [Quartz 5](https://quartz.jzhao.xyz/) 建置的公開 Obsidian 筆記網站。

## 發布筆記

1. 只把確認可公開的筆記與必要附件複製到 `content/`。
2. `content/` 內的 Markdown 會自動發布；不想發布的單篇筆記請設定 `draft: true`。
3. 執行 `npx quartz build` 本機檢查後再提交。

圖片、PDF、音訊等非 Markdown 檔案仍可能被公開，因此不要把未審核的附件放進 `content/`。
