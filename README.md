# 森SHEN 內容定位 & 題材系統

森SHEN 植萃保養（@shen_official_tw）的內容知識庫、給團隊和 Claude 一起用、收斂內容方向、產出不重複的短影音題材。

## 這是什麼？

不是一般的程式專案、是一個**結構化的 markdown 知識庫**。團隊（老闆、小編、設計、攝影）和 Claude 都讀寫同一批檔、決定下一支拍什麼、避免重複。

## 怎麼用？

1. **第一次來**：先讀 `CLAUDE.md`（通用規則）和 `CLAUDE.local.md`（森SHEN 設定）
2. **要發想題材**：開新對話、跟 Claude 說「用 `06-prompts/topic-ideation.md` 幫我發想」
3. **要寫腳本**：開新對話、跟 Claude 說「用 `06-prompts/script-draft.md` 幫我寫」
4. **盤點過去內容**：跑 `06-prompts/axis-mapping.md`

## 目錄速查

| 資料夾 | 放什麼 |
|---|---|
| `01-brand/` | 品牌定位、客群、語氣（少改） |
| `02-inventory/` | 過去 508 貼文盤點 |
| `03-axis-map/` | 內容軸地圖、現有 + 延伸 + 不碰 |
| `04-topics/` | 題材池（待拍 / 已拍 / 節慶） |
| `05-scripts/` | 短影音腳本草稿 |
| `06-prompts/` | 給 Claude 的標準範本 |

## 規則最重要的三條

1. 保養品**禁用療效詞**、寫之前先過 `01-brand/voice.md`
2. 不在資料裡的事實**不要編**、查不到問人
3. 改之前**先講方案**、不要直接動 CSV / 結構

詳細規則看 `CLAUDE.md`。
