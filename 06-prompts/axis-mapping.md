# Prompt：內容軸盤點 + 延伸軸提案

> 用途：盤點 `02-inventory/content-log.csv`、產出 `theme-stats.md`、
> 並提案 `extended-axes.md` 候選軸。

---

## 給 Claude 的工作指令

請依下列順序執行、每一步完成後**先報告、等使用者確認**再進下一步。

### Step 0：讀資料

讀完才動：
1. `01-brand/positioning.md`
2. `01-brand/audience.md`
3. `01-brand/voice.md`
4. `02-inventory/content-log.csv`
5. `03-axis-map/current-axes.md`（若有）
6. `03-axis-map/taboo.md`

### Step 1：CSV 統計

跑出：
- 總貼文數、時間範圍
- 各 `main_axis` 的出現次數、佔比
- 各軸的平均互動（likes + comments + saves + shares）/ reach
- 表現最好的 5 軸、表現最差的 5 軸
- 出現少於 5 次的「邊緣軸」

寫入 `02-inventory/theme-stats.md`、覆蓋舊內容。

### Step 2：診斷現況

用一句話回答：
1. 森SHEN 過去最常做哪幾條軸？
2. 哪些軸做得多、但互動低（過飽和）？
3. 哪些軸做得少、但互動高（值得加碼）？
4. 哪些主題完全沒做過、但符合品牌定位？

### Step 3：延伸軸提案

依下列規則、提 5 條候選延伸軸寫入 `03-axis-map/extended-axes.md`：

**每條候選必須：**
1. 跟「植萃 / 肌膚」有清楚關聯（一句話說得通）
2. 跟 `audience.md` 客群關心的事情對得上
3. 不踩 `taboo.md` 紅線
4. 跟既有軸夠不一樣（避免換湯不換藥）
5. 給出「試水溫」做法（拍 1-2 支看反應的具體方向）

**輸出格式**：依 `extended-axes.md` 內已有的欄位填、不要自創。

### Step 4：等使用者投票

不要自己決定、列出 5 條讓團隊投票留 3 條。

---

## 紅線

- 不在 CSV 裡的數據不要編
- 不要直接動 `current-axes.md`、那是團隊決定的
- 統計過程若 CSV 欄位異常、停下、回報、不要硬跑
