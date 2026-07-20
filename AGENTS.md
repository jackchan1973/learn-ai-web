# 學習AI網頁 — 專案工作規則

> Claude 讀 `CLAUDE.md`、Codex 讀 `AGENTS.md`，**兩份內容完全相同**。改規則時兩份一起改。
> 共同開發：Claude 與 Codex 都對這個資料夾開發，靠 git 記錄誰改了什麼——動工前先 `git pull`，做完先 `git push`，避免兩邊各改各的。

## 專案是什麼

- 主題「學習 AI，和未來一起成長」的**單機互動網頁**，給老師與朋友的 AI 入門分享。
- 目標：教不會寫程式的人——認識 AI → 裝好工具（Claude／Codex 桌面端）→ 寫自己的規則（CLAUDE.md／AGENTS.md）→ 看實戰案例。

## 位置與網址

- 本機資料夾：`~/開發項目/學習AI網頁/`（2026-07-20 從 `learn-ai-web` 改中文名）
- 主程式：`index.html`（單一 HTML，內嵌 CSS/JS，手機電腦皆可）
- 線上網址：https://jackchan1973.github.io/learn-ai-web/
- GitHub repo：`jackchan1973/learn-ai-web` — **repo 英文名不可改**（改了線上網址會壞）；本機中文資料夾名不影響網址。

## 檔案結構

```text
index.html                         # 單一主程式（內嵌 CSS/JS）
assets/                            # 圖片素材（Claude/Codex logo、桌面截圖、MD 截圖、封面 cover.jpg）
downloads/                        # 可下載的 Skill 安裝說明 md
2026-07-13_學習AI網頁_開發案例.md    # 開發案例文件（隨 repo）
```

- 版面 7 區塊：Hero（首頁快速進入）→ 什麼是 AI（三層）→ AI 安裝（Claude／Codex 桌面端大分頁）→ MD 文件（CLAUDE.md／AGENTS.md）→ ⭐MD 範本產生器 → 做自己的 Agent（一句指令 8 步配方）→ 案例分享／製作案例。
- 配色：深色 `#1c1815` + 磚橘 terracotta `#c8724f` + 米色卡片（沿用簡報風格）。

## 開發鐵則

1. **範圍固定**：只做 Claude／Codex **桌面端**，不做終端機版；**不含** Plugins & Skills、Subagent。
2. **純靜態網頁**：改 HTML 後在瀏覽器確認即可，沒有後端與建置步驟。
3. **素材來源**：`assets/` 圖來自 `~/Desktop/AI安裝教程/` 的簡報；要換圖先確認來源。
4. 改完直接 `git push` 更新 GitHub Pages。

## 發佈

本機瀏覽器看過 OK → 只 `git add` 改到的檔 → `git commit` → `git push`，GitHub Pages 約 1–2 分鐘生效。

## 文件分工

- `CLAUDE.md` / `AGENTS.md`：工作規則（本檔），兩份相同。
- `2026-07-13_學習AI網頁_開發案例.md`：開發案例與過程紀錄。
