# Emergency First-Aid Knowledge Base - Project Rules & Guidelines

## 1. 專案目的 (Project Objective)
建立一個專門收錄與展示緊急急救知識、技術指引與常見應變步驟的互動式網頁筆記庫，方便隨時查閱與向大眾推廣正確的急救觀念。

## 2. 網頁整體風格 (Design & Style)
- **視覺風格**：簡潔、專業、響應式設計（RWD），適合手機與電腦瀏覽。
- **色彩搭配**：以醫療專業的藍、白為主色調，搭配醒目的警戒色（如橘紅色）作為重點提示。
- **排版框架**：使用 Tailwind CSS 或簡潔的 CSS 樣式，確保卡片式排版清晰易讀。

## 3. 頁面結構 (Page Structure)
- `index.html`：首頁，展示專案介紹與急救主題總覽卡片。
- `cpr.html`：CPR 與 AED 操作指南頁面。
- `bleeding.html`：大出血與包紮處理指引頁面。

## 4. 新增內容時要遵守的格式 (Content Format)
當新增一個急救主題頁面時，必須包含以下區塊：
1. **情境說明**：何時該使用此急救技術。
2. **標準步驟 (Step-by-Step)**：以有序清單 (`<ol>`) 列出明確的動作。
3. **注意事項 (Warnings)**：以紅色警示框標註絕對不可做的行為。

## 5. 檔案命名與放置 (File Naming & Placement)
- 所有 HTML 頁面均放在根目錄下。
- 頁面命名使用全小寫英文連字號（例如：`cpr-guide.html`, `choking-relief.html`）。
- 樣式與腳本統一放入 `assets/` 資料夾（如 `assets/style.css`）。

## 6. AI 修改或新增規則 (Rules for AI)
- 當使用者要求新增一個急救項目時，必須自動生成符合上述「4. 新增內容時要遵守的格式」之 HTML 結構。
- 必須確保所有內部連結（Navbar 導覽列）在新增頁面後同步更新。
