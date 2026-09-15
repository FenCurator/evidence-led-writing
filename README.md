# 證據導向寫作（Evidence-Led Writing）

一個相容於 Hermes Agent 的寫作 skill，協助你寫出**容易閱讀、具備判斷力，而且不超出來源證據範圍**的報導、簡報與內容。

## 這個 skill 做什麼？

- 讓語氣強度與證據強度相稱。
- 使用 Evidence Spine（證據脊骨）組織文章，避免把同時發生誤寫成因果關係。
- 用具體細節與可驗證數字取代空泛形容詞。
- 協助文章建立開頭張力、讀者關聯與決策意義。
- 在發布前執行 Counter-editor（反方編輯）檢查。
- 區分 Fact、Observation、Interpretation 與 Recommendation。

## 適用情境

適合用於：

- AI 或科技生態日報
- 新聞摘要與研究簡報
- 長篇報導與分析文章
- 社群貼文與電子報
- 需要查證、判斷與清楚表達的腳本

這個 skill **不會取代**資料蒐集、來源查證或編輯判斷；它主要規範寫作過程、證據校準與完稿檢查。

## 安裝到 Hermes

可以直接從 GitHub 安裝：

```bash
hermes skills install \
  https://raw.githubusercontent.com/FenCurator/evidence-led-writing/main/SKILL.md
```

也可以手動將 `SKILL.md` 複製到 Hermes 的 skill 目錄。

## 核心方法

### 1. 證據等級決定語氣等級

- **[F] Fact**：來源直接說明的事實。
- **[O] Observation**：根據多個事實整理出的觀察。
- **[I] Interpretation**：作者的判斷，需列出替代解釋。
- **[R] Recommendation**：會影響讀者決策的建議，需交代條件與驗證狀態。

**不要讓句子的確定程度超過證據能支持的程度。**

### 2. Evidence Spine

每條主要論述依序檢查：

```text
先前判斷 → 新增證據 → 反證／替代解釋 → 信心變化 → 決策意義
```

### 3. Counter-editor

完稿後反問自己：

1. 我是否把同時發生寫成了因果？
2. 哪一句最像標題黨？刪掉修辭後還成立嗎？
3. 反方最容易從哪個數字、來源層級或定義反駁？

## 特性

這個 skill 是自包含的，不要求：

- API key
- 私人檔案
- 特定搜尋服務
- 特定模型
- 特定作業系統

## 授權

MIT License，詳見 [LICENSE](LICENSE)。
