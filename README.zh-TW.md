# 🎪 html-ppt-plan · HTML 簡報工作室

> 基於 [lewislulu/html-ppt-skill](https://github.com/lewislulu/html-ppt-skill) 客製化版本  
> 由 cw33c2 維護，整合至 Antigravity soil-html-deck 技能體系

**36 套主題** × **15 套完整 deck 模板** × **36 種頁面版型** × **47 種動畫特效** + **演講者模式（逐字稿 + 計時器）**

---

## ✨ 本版本特色

- 保留 lewis 原版全部資源（主題、模板、特效）
- 整合說明對應 `soil-html-deck` 技能使用情境
- 繁體中文說明文件

---

## 🔀 與 soil-html-deck 的分工

| | soil-html-deck | html-ppt-plan |
|--|---------------|---------------|
| **定位** | SOIL 教學框架 + AI 生圖 | 設計資產庫 + 視覺模板 |
| **主題** | 1 種（深色霓虹） | **36 種** |
| **AI 生圖** | ✅ gpt-image-2/fal-ai | ❌ 純代碼視覺 |
| **即時互動** | ✅ Firebase 文字雲/投票 | ❌ |
| **演講者模式** | ❌ | ✅ S鍵 + 逐字稿 + 計時器 |
| **Canvas 特效** | ❌ | ✅ 20 種 |
| **適合** | 教師研習、課程教學 | 技術分享、產品發布、小紅書 |

---

## 🎨 36 套主題一覽

依使用場景分類：

| 場景 | 推薦主題 |
|------|---------|
| 投資人簡報 | `pitch-deck-vc`、`corporate-clean`、`swiss-grid` |
| 技術分享 | `tokyo-night`、`dracula`、`catppuccin-mocha`、`terminal-green`、`blueprint` |
| 小紅書圖文 | `xiaohongshu-white`、`soft-pastel`、`rainbow-gradient`、`magazine-bold` |
| 學術/報告 | `academic-paper`、`editorial-serif`、`minimal-white` |
| 潮流/賽博龐克 | `cyberpunk-neon`、`vaporwave`、`y2k-chrome`、`neo-brutalism` |

---

## 📑 15 套完整 Deck 模板

### 從真實作品提煉（8 套）
| 模板 | 風格 |
|------|------|
| `xhs-white-editorial` | 小紅書白底雜誌風 |
| `graphify-dark-graph` | 暗底 + 力導向知識圖譜 |
| `hermes-cyber-terminal` | 終端機 Cyberpunk 風 |
| `obsidian-claude-gradient` | 紫色漸層卡 |
| `testing-safety-alert` | 紅/琥珀警示風 |
| `xhs-pastel-card` | 柔和馬卡龍圖文 |
| `knowledge-arch-blueprint` | 藍圖/架構圖風 |
| `dir-key-nav-minimal` | 方向鍵極簡風 |

### 通用場景（7 套）
| 模板 | 用途 |
|------|------|
| `pitch-deck` | 投資人提案 |
| `product-launch` | 產品發布會 |
| `tech-sharing` | 技術分享 |
| `weekly-report` | 週報 |
| `xhs-post` | 小紅書圖文（9頁 3:4）|
| `course-module` | 教學模組 |
| `presenter-mode-reveal` 🎤 | 含逐字稿示例的演講者模板 |

---

## 🎤 演講者模式（按 `S` 鍵）

任何 deck 按下 `S`，彈出包含 4 個可拖曳卡片的獨立視窗：

| 卡片 | 說明 |
|------|------|
| 🔵 **CURRENT** | 當前頁像素級預覽 |
| 🟣 **NEXT** | 下一頁預覽 |
| 🟠 **SPEAKER SCRIPT** | 逐字稿（大字，可捲動） |
| 🟢 **TIMER** | 計時器 + 頁碼 + 前後按鈕 |

**逐字稿三原則：**
1. 提示信號，不是講稿 — 關鍵詞加粗、過渡句獨立成段
2. 每頁 150–300 字 — 約 2–3 分鐘/頁節奏
3. 用口語，不用書面語 — 「所以」不是「因此」

---

## 💥 20 種 Canvas 特效

透過 `data-fx="<特效名>"` 加在任何頁面元素上觸發：

| 特效 | 視覺效果 |
|------|---------|
| `particle-burst` | 粒子爆炸 |
| `confetti-cannon` | 彩紙大砲 🎊 |
| `firework` | 煙火 |
| `starfield` | 星空飛行 |
| `matrix-rain` | 綠色代碼雨 |
| `neural-net` | 神經網絡脈衝 |
| `galaxy-swirl` | 星系漩渦 |
| `typewriter-multi` | 多行打字機 |
| `counter-explosion` | 數字爆炸 |
| `knowledge-graph` | 力導向知識圖譜 |

---

## ⌨️ 鍵盤快捷鍵

| 按鍵 | 功能 |
|------|------|
| `← →` | 翻頁 |
| `S` | 開啟演講者模式 |
| `T` | 循環切換主題 |
| `F` | 全螢幕 |
| `O` | 投影片總覽 |
| `N` | 備注抽屜 |

---

## 🚀 快速開始

```bash
# 建立新 deck
./scripts/new-deck.sh my-talk
# 在瀏覽器開啟
start examples/my-talk/index.html
```

切換主題（換一行 HTML）：
```html
<link rel="stylesheet" id="theme-link" href="../assets/themes/tokyo-night.css">
```

---

## 📄 授權

原作者：[lewis](https://github.com/lewislulu/html-ppt-skill)（MIT License）  
本版本維護：cw33c2
