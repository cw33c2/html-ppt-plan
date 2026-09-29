---
title: HTML 三大工具架構與協作指南 (soil-html-deck x html-ppt-plan x Polyglot-Dharma-Translator)
tags:
  - AI工具
  - HTML簡報
  - 工作流
  - 系統架構
date: 2026-09-29
---

# 🛠️ HTML 三大工具架構與協作指南

本指南說明 `soil-html-deck`、`html-ppt-plan` 與 `Polyglot-Dharma-Translator` 三大 HTML 相關專案與技能的核心定位、功能區分與協作模式。

---

## 🎯 一、 核心定位與區分一覽

| 專案 / 技能名稱 | 核心角色（白話比喻） | 處理的 HTML 類型 | 適用情境與時機 |
| :--- | :--- | :--- | :--- |
| **`Polyglot-Dharma-Translator`** | 🧠 **內容與翻譯大腦** <br>(內容提供者) | 多語系對照網頁、逐字稿、結構化文本 HTML | 需要多語系翻譯、字幕對照、文本對齊、內容翻譯時 |
| **`soil-html-deck`** | 🎓 **教學互動簡報大師** <br>(教學骨架與互動靈魂) | 結合 SOIL 引擎與 Reveal.js 的**互動教學 HTML 投影片** | 做研習、教學課程、需要學員即時互動（投票/文字雲）時 |
| **`html-ppt-plan`** | 🎨 **視覺特效與主題庫** <br>(視覺皮膚與特效資產) | 36 套 CSS 主題、20 種 Canvas 特效、36 種純代碼版型 | 需要極致視覺設計、賽博龐克/小紅書風、S鍵講者提詞器時 |

---

## 🎬 二、 劇组角色分工

* ✍️ **`Polyglot-Dharma-Translator`（編劇/翻譯團隊）**
  * **職責**：提供優質且精準的多語系內容素材，輸出乾淨的對照文本。
* 🎬 **`soil-html-deck`（導演/教學設計師）**
  * **職責**：掌控教學節奏。運用 SOIL 六引擎與林長揚 30 原則，規劃引起動機、維持注意、喚起行動，並插入學員互動標記 `[INTERACT]`。
* 🎨 **`html-ppt-plan`（造型師/特效總監）**
  * **職責**：提供強大的視覺皮膚（36 套主題）與炫酷的 Canvas 特效（粒子、星空、代碼雨），並提供講師專用的「S 鍵演講者提詞面板」。

---

## 🔄 三、 黃金協作工作流 (Workflow)

當需要進行一場**跨國/多語系的線上互動講座或技術分享**時，三大工具的串聯流程如下：

```mermaid
flowchart TD
    A[Step 1: 內容產出與翻譯\nPolyglot-Dharma-Translator] -->|輸出多語系文本/ Markdown| B[Step 2: 結構與互動規劃\nsoil-html-deck]
    B -->|套用 SOIL 引擎 & 規劃 [INTERACT] 標記| C[Step 3: 視覺皮裝與演講準備\nhtml-ppt-plan]
    C -->|借用 36 套主題 CSS / Canvas 特效 / S鍵提詞器| D((產出完美 HTML 簡報))
```

### 協作步驟說明：
1. **內容階段**：用 `Polyglot-Dharma-Translator` 處理多語系講稿或文案。
2. **結構階段**：用 `soil-html-deck` 建立簡報骨架，規劃 `[BG]` 底圖與 `[INTERACT:wordcloud]` 學員互動文字雲。
3. **視覺與演講階段**：借用 `html-ppt-plan` 的主題（如 `tokyo-night`）與特效（如 `starfield` 星空），並開啟 `S 鍵演講者模式` 讓講師看逐字稿與計時器報告。

---

## 💬 四、 給 AI 的下達口令 (Prompt Guide)

### 1. 單一使用情境：
* **翻譯/多語系網頁**：
  > *「請用 `Polyglot-Dharma-Translator` 幫我翻譯這篇講義並輸出對照網頁。」*
* **教學研習/互動簡報**：
  > *「請用 `soil-html-deck` 幫我把這份素材做成包含 Firebase 互動文字雲的課程簡報。」*
* **極致視覺/技術分享/講者提詞**：
  > *「請用 `html-ppt-plan` 的 tokyo-night 主題做一份技術分享簡報，並幫我寫好演講者逐字稿。」*

### 2. 三大工具協作情境：
> *「請先用 `Polyglot-Dharma-Translator` 整理多語系講稿，接著以 `soil-html-deck` 的教學架構規劃簡報骨架與互動投票，最後借用 `html-ppt-plan` 的賽博龐克主題與 Canvas 特效完成最終 HTML 簡報！」*

---

## 📌 相關連結與路徑

* **`soil-html-deck`**: `C:\Users\ASUS\.gemini\config\skills\soil-html-deck\`
* **`html-ppt-plan`**: 
  * 本地目錄：`C:\Users\ASUS\Documents\html-ppt-plan`
  * GitHub 庫：[https://github.com/cw33c2/html-ppt-plan](https://github.com/cw33c2/html-ppt-plan)
  * Skill 配置：`C:\Users\ASUS\.gemini\config\skills\html-ppt\`
* **`Polyglot-Dharma-Translator`**: 內容與翻譯工具庫
