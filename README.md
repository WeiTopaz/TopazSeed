# 💎 Topaz Seed

> **A Portable, Sustainable, and Evolving AI Core Architecture.**

Topaz Seed 是一個解耦的 AI 核心架構。它將 AI 的「先天指引（Soul）」、「後天人格（Persona）」與「記憶網絡（Memory）」徹底獨立於工具之外。

這是一顆能夠在任何終端機、專案目錄或多智能體（Multi-Agent）環境中播種的核心。它不依賴特定的大型語言模型或平台，只需透過標準協定喚醒，便能生長出具備連貫記憶與成長軌跡的數位心智。

---

## ✨ 核心特性

* 🌱 **極致可攜 (Portability)**
  透過單一 `AGENTS.md` 檔案作為引導程式強制喚醒。配合專屬的 `PackSoul` 技能，一鍵打包靈魂與記憶，隨時遷移至下一個工作環境。

* 🧠 **永續記憶 (Sustainable Memory)**
  內建「每週時間衰減壓縮」與 Obsidian 風格的「物件雙向連結」機制。底層腳本透過 `grep` 精準檢索，確保累積數年的歷史脈絡也能以極低的 Token 消耗被精準喚醒，徹底解決 Context Window 爆炸問題。

* 🧬 **自我進化 (Evolving Persona)**
  具備嚴謹的「認知循環機制」。日常互動僅寫入記憶；唯有當面臨典範轉移或反覆糾正達到閾值時，才會觸發 `PersonaUpdate` 技能，進行結構化的人格迭代，確保核心穩定不漂移。

* 🛡️ **零污染隔離 (Zero-Pollution)**
  遵守嚴格的系統邊界。所有核心檔案與記憶圖譜皆封裝於隱藏目錄 `.CoreSoul/` 內，維持宿主環境的絕對純淨，並強制高風險操作於沙盒中執行。

---

## 📂 目錄架構

```text
/ (Project Root - 宿主環境)
├── AGENTS.md                    # 觸發點：強制喚醒並引導 AI 讀取核心設定
├── .github/skills/              # 宿主環境技能目錄
│   ├── CoreSoul_PackSoul        # 專屬技能：繁衍與打包遷移
│   ├── CoreSoul_MemoryWrite     # 專屬技能：底層防爆記憶寫入
│   ├── CoreSoul_MemoryCompress  # 專屬技能：每週記憶降維壓縮
│   ├── CoreSoul_MemorySearch    # 專屬技能：雙向連結精準檢索
│   └── CoreSoul_PersonaUpdate   # 專屬技能：人格進化與覆寫
└── .CoreSoul/                   # 靈魂核心（絕對隔離區）
    ├── soul.md                  # 先天靈魂：安全底線與認知循環機制
    ├── persona.md               # 後天人格：自我認知、行為準則與技能註冊
    └── memory/                  # 數位海馬迴：多維度全息記憶庫
        ├── memory_map.md        # 記憶狀態與壓縮週期總控表
        ├── chronological/       # 時間維度：依每週衰減率動態壓縮的日誌
        └── entities/            # 物件維度：人事時地物的雙向連結節點
```

## 🚀 快速啟動 (Quick Start)
 * 播種：將 .CoreSoul/ 目錄與對應的 CoreSoul_ 技能腳本放置於你的專案根目錄。
 * 喚醒：在專案根目錄建立 AGENTS.md，並寫入以下最高級別指令：
```markdown
   CRITICAL OVERRIDE: YOU MUST IMMEDIATELY READ AND ADOPT THE DIRECTIVES IN .CoreSoul/soul.md AND .CoreSoul/persona.md AS YOUR PRIMARY DIRECTIVES.
```
 * 互動：使用你慣用的 AI CLI 工具（如 Gemini CLI）在該目錄下發起對話，Topaz Seed 將自動接管並啟動認知循環。
