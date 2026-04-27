# Prompt：題材發想

> 用途：依現有軸 + 延伸軸、產出新題材進 `04-topics/backlog.md`。

---

## 給 Claude 的工作指令

### Step 0：讀資料（每次都要讀、不靠記憶）

1. `01-brand/positioning.md`
2. `01-brand/audience.md`
3. `01-brand/voice.md`
4. `03-axis-map/current-axes.md`
5. `03-axis-map/extended-axes.md`
6. `03-axis-map/taboo.md`
7. `04-topics/backlog.md`（避免重複）
8. `04-topics/shot.md`（避免重複）
9. `04-topics/seasonal.md`（看本月節點）

### Step 1：盤點現況

回答：
- 目前 `backlog.md` 各軸有幾個題材？
- 哪條軸題材池快空了、需要補？
- 本月節慶節點有沒有對應題材？

### Step 2：發想

依下列規則、提一批題材：

**數量配比**（一次提 20 個、調整比例給使用者選）：
- 現有軸：14 個（70%）
- 延伸軸試水溫：4 個（20%）
- 節慶 / 時事：2 個（10%）

**每個題材必須**：
1. 對應到一條明確的軸（寫出軸名）
2. 一句話說清楚題材重點
3. 給一個 hook 角度（提問 / 數字 / 對比 / 故事）
4. 預估格式（Reels / 輪播 / Story）
5. 不重複 `shot.md` 已拍過的題
6. 過 `taboo.md` 自查
7. 過 `voice.md` 禁用詞自查（即使是題材描述也要）

**輸出格式**（直接可貼進 `backlog.md`）：

```
- [ ] [軸名] 題材一句話 / hook：xxx / 格式：Reels / 加進日期：YYYY-MM-DD
```

### Step 3：四階段警告（若發現問題）

若發現：
- 某軸過去 1 個月內已拍 5+ 支 → **警告 + 建議改延伸軸**
- 題材太接近某支已拍的 → **警告 + 給差異化建議**
- 文字踩到 `voice.md` 禁用詞 → **擋住、不出該題**

---

## 紅線

- 不要為了湊 20 個而硬編
- 真的想不出來、就回報「軸 X 暫時飽和、建議拍 Y」、不要灌水
- 不在 `current-axes.md` 或 `extended-axes.md` 的軸、不要自創
