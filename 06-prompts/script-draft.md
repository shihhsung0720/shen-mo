# Prompt：短影音腳本草稿

> 用途：把 `04-topics/backlog.md` 的一個題材、寫成可拍的腳本。
> 輸出存到 `05-scripts/`。

---

## 給 Claude 的工作指令

### Step 0：讀資料

1. `01-brand/positioning.md`
2. `01-brand/audience.md`
3. `01-brand/voice.md`（**重點：禁用詞清單**）
4. 對應的軸定義（`03-axis-map/current-axes.md` 或 `extended-axes.md`）
5. `03-axis-map/taboo.md`
6. `04-topics/shot.md`（看相近題以前怎麼拍）

### Step 1：確認題材

讓使用者提供：
- 題材一句話（或從 `backlog.md` 指定哪一個）
- 預期長度（15s / 30s / 60s）
- 預期格式（Reels / Story）
- 是否要提到產品（哪一支）

### Step 2：寫腳本

依下列結構：

```markdown
# 腳本：[題材]

- 軸：xxx
- 長度：xx 秒
- 格式：Reels
- 提到產品：xxx（或無）
- 草稿日期：YYYY-MM-DD

## Hook（前 3 秒）
（一句話、可以是疑問 / 數字 / 反差）

## 主體（中段）
（資訊或故事、分 2-4 個 beat、每 beat 一句話）

beat 1：
beat 2：
beat 3：

## 收尾 + CTA
（一句話收 + 行動呼籲）

## B-roll / 鏡位建議
- 0-3s：xxx
- 3-15s：xxx
- 15-30s：xxx

## 字幕重點（3-5 句、配合鏡頭）
1.
2.
3.

## 自查記錄
- [ ] 過 voice.md 禁用詞清單
- [ ] 過 taboo.md
- [ ] 對應軸：xxx
- [ ] 跟 shot.md 已拍題不重複
```

### Step 3：自查

寫完**強制**自己跑一次：

1. 對照 `voice.md` 禁用詞、命中 = 改、不要自己放行「應該還好」
2. 對照 `taboo.md`、命中 = 整支重寫
3. 語氣是否溫柔、有沒有販賣焦慮 / 恐嚇
4. 有沒有對應到一條軸、軸名寫對

**任何疑慮 → 在腳本頂部標記 `⚠ 待人工確認`、不要自己決定**。

### Step 4：存檔

存到 `05-scripts/YYYY-MM-DD_<軸縮寫>_<題材關鍵字>.md`。
未發布加 `draft-` 前綴（會被 .gitignore 排除）。

---

## 紅線

- 禁用詞自查**不可省略**、即使「我覺得這個 OK」也要走完
- 不要自創產品名、產品功效未在 `01-brand/` 寫的、要問人
- 不要假裝有客戶見證 / 用戶數據、沒有就不要寫
