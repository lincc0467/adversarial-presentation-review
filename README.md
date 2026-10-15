# Adversarial Presentation Review

一個 Claude skill：在簡報、提案或 pitch deck 正式發表前，做對抗式審查。

## 流程

1. **收集背景**：從上傳的簡報讀出目的、聽眾、時間、期望行動等，只追問缺少的關鍵資訊。
2. **Grill Me**：五輪逐題盤問，每輪一題，用目標聽眾的角度找出最脆弱的論點。
3. **深入分析**：核心問題排序、值得放大的優勢、SWOT、三維度評分（論點與證據／架構與順序／表達與溝通）、目的達成度。
4. **重新設計**：模式 A 只給架構，模式 B 直接產出新簡報；缺少的證據一律標「【待補：…】」，不編造數據。

## 安裝

把 `SKILL.md` 放進 skill 資料夾即可，例如：

- Claude Code：`~/.claude/skills/adversarial-presentation-review/SKILL.md`
- Claude.ai：在 Settings → Capabilities → Skills 上傳包含 `SKILL.md` 的資料夾（zip）

## 使用

上傳簡報後說「幫我審查這份簡報」或「發表前幫我演練一下」，Claude 會自動載入這個 skill。
