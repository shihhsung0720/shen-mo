# Prompt 範本：內容軸盤點 axis-mapping

> 用途：給 Claude 一批過去貼文，請他歸納出現有內容軸 + 找空白。
> 產出放：`03-axis-map/current-axes.md` 跟 `extended-axes.md`

---

## 使用方式

1. 把要分析的貼文資料整理成 CSV（參考 `02-inventory/content-log.csv` 格式）
2. 把以下 prompt 連同 CSV 一起貼給 Claude
3. 拿到結果，跟現有 `current-axes.md` 對照，更新

---

## Prompt

```
你是森SHEN 品牌的內容策略分析師。

【背景】
請先讀以下三個檔案理解品牌：
- 01-brand/positioning.md
- 01-brand/audience.md
- 01-brand/voice.md
紅線清單：03-axis-map/taboo.md（不能踩）

【任務】
我給你一批過去的貼文資料（CSV），請你：

1. **歸納現有內容軸**
   - 列出 3-5 條主要軸線
   - 每條軸註明：典型題、平均互動、佔比

2. **找出做爛的題**
   - 出現次數 ≥ X 次但互動 < 平均
   - 為什麼可能做爛？

3. **找出紅題**
   - 互動明顯高於平均的少數題
   - 共通模式是什麼？是否可以複製？

4. **找出空白**
   - 對照 audience.md 的痛點，哪些痛點目前內容沒覆蓋？
   - 建議 2-3 條延伸軸

5. **給出健康度評估**
   - 每條軸標：紅（停 / 改型）、黃（OK 但可加角度）、綠（加倍投入）

【輸出格式】
直接 Markdown，可以貼進 03-axis-map/ 的對應檔案。

【貼文資料】
（這裡貼 CSV）
```
