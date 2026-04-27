# CLAUDE.md — 給 AI 與接手者的工作規則

## 這個 repo 是什麼

森SHEN 品牌的內容策略 / 短影音腳本工作空間。所有產出（題材、腳本、文案）必須符合品牌語氣與紅線。

## 動任何事之前，先讀這三個

1. `01-brand/voice.md` — 文案語氣、用詞紅線
2. `01-brand/positioning.md` — 品牌定位、USP（含 ECOCERT / SGS）
3. `03-axis-map/taboo.md` — 不能碰的題材

## 紅線（永遠不要做）

- **療效宣稱**：治癒、根治、療效、改善 XX 病、抗 XX 病等
- **誇大效果**：100%、立刻、瞬間、神效、奇蹟
- **政治、宗教、競品**：不評論、不比較、不影射
- **未經證實的具體數字**：除非有來源並標註出處
- **個資外洩**：客戶姓名、訂單編號、私訊截圖

## 檔案編號規則

- `01-` 穩定不太動的（品牌核心）
- `02–04` 動態進行中的（盤點、地圖、題材）
- `05–06` 執行用的（腳本、prompt 範本）

## 標準工作流

| 任務 | 用哪個範本 | 產出放哪 |
|---|---|---|
| 整理現有內容軸 | `06-prompts/axis-mapping.md` | `03-axis-map/current-axes.md` |
| 想新題材 | `06-prompts/topic-ideation.md` | `04-topics/backlog.md` |
| 寫短影音腳本 | `06-prompts/script-draft.md` | `05-scripts/YYYY-MM-DD-題目.md` |

## Commit 規範

- `brand:` 改 `01-brand/` 內容
- `inventory:` 改 `02-inventory/`
- `axis:` 改 `03-axis-map/`
- `topic:` 改 `04-topics/`
- `script:` 改 `05-scripts/`
- `prompt:` 改 `06-prompts/`
- `docs:` 改 README / CLAUDE.md
- `chore:` 雜項

## 給 AI 的額外提醒

- 產出短影音腳本時：**先確認題材不在 `taboo.md` 裡**
- 用詞前**先查 `voice.md` 的紅線**
- 不確定就停下來問，不要硬寫
