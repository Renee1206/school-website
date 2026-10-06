# 🏫 School Website｜校園資訊網站

以高中校園資訊服務為主題設計的多頁式網站，使用 HTML、CSS 與 JavaScript 建置，整合學校介紹、行政單位、新生資訊、最新消息、重要公告與行事曆等內容。

網站除了基本的資訊呈現外，也加入圖片輪播、多層導覽選單、站內導覽搜尋、字體大小調整、PDF 文件預覽與下載、Google Calendar、YouTube / Facebook 嵌入及回到頂部等互動功能，提升校園資訊整合性與使用者瀏覽體驗。

---

## ✨ Features｜主要功能

### 🏠 首頁

- 校園活動圖片自動輪播
- 最新消息資訊展示
- 重要公告卡片
- 常用校園資源快速連結
- 多層式下拉導覽選單
- 固定式導覽列（Sticky Navigation）
- 網站內容搜尋
- A- / A / A+ 字體大小調整
- 浮動式「回到頂部」按鈕

### 🏫 認識東中

提供學校相關資訊，包括：

- 校長資訊
- 校徽與設計理念
- 校訓
- 學校介紹
- 校園特色
- 校園環境照片
- 校歌
- 校園平面圖
- YouTube 校園空拍影片
- Facebook 粉絲專頁

### 🏢 行政單位

整理各行政單位的基本資訊、聯絡方式與相關官方網站，包括：

- 校長室
- 教務處
- 學務處
- 總務處
- 輔導處
- 圖書館
- 人事室
- 主計室
- 教官室
- 進修部

### 🎓 新生專區

整合新生入學所需的重要資訊，包括：

- 新生重要時程
- 新生線上預填報到
- 專班調查
- 暑假作業
- 新生報到手冊
- 特殊身分減免相關文件
- 專車申請資訊
- 宿舍申請資訊
- 新生健康檢查相關文件

### 📅 行事曆

- 學生版行事曆
- 教職員行事曆
- 團體活動課程表
- PDF 線上預覽
- PDF 檔案下載
- Google Calendar 行事曆嵌入

### 🔍 網站搜尋

使用 JavaScript 搜尋導覽列與網站選單中的項目，並透過 Dialog 顯示搜尋結果。

### 🔠 字體大小調整

提供：

- `A-`：縮小字體
- `A`：恢復預設大小
- `A+`：放大字體

方便不同使用者依閱讀需求調整網站文字大小。

### 📱 Responsive Design

使用 CSS Grid 與 Media Query 製作響應式版面，在較小螢幕下會將原本的多欄式版面重新排列為單欄顯示。

---

## 🛠️ Technologies｜使用技術

| Technology | Description |
|---|---|
| HTML5 | 網頁結構與內容 |
| CSS3 | 網頁排版、動畫與響應式設計 |
| JavaScript | 搜尋、字體調整、下載、回到頂部等互動功能 |
| jQuery | 首頁圖片輪播控制 |
| CSS Grid / Flexbox | 網站版面配置 |
| Font Awesome | 導覽列及功能圖示 |
| Google Calendar | 校務行事曆嵌入 |
| YouTube Embed | 校園影片播放 |
| Facebook Embed | Facebook 粉絲專頁整合 |

---

## 📂 Project Structure

```text
school-website/
│
├── index.html
│   └── 網站首頁、最新消息、重要公告與圖片輪播
│
├── school-profile.html
│   └── 學校介紹、校徽、校訓、校園特色與校園影音
│
├── administrative-offices.html
│   └── 各行政單位資訊
│
├── new-students.html
│   └── 新生入學相關資訊與文件
│
├── academic-calendar.html
│   └── 校務行事曆、PDF 預覽與 Google Calendar
│
├── css/
│   └── site.css
│       └── 網站共用樣式與 Responsive Layout
│
├── img/
│   └── 網站使用的圖片與圖示
│
└── file/
    └── 行事曆、新生手冊及相關 PDF 文件
```

---

## 🚀 Getting Started｜執行方式

本專案為純前端靜態網站，不需要安裝額外套件。

### 1. Clone Repository

```bash
git clone https://github.com/Renee1206/school-website.git
```

### 2. 進入專案資料夾

```bash
cd school-website
```

### 3. 開啟網站

直接使用瀏覽器開啟：

```text
index.html
```

或使用 Visual Studio Code 的 **Live Server** 開啟網站。

> 部分功能會載入 Font Awesome、jQuery、Google Calendar、YouTube、Facebook 及學校官方網站等外部資源，因此建議在有網路連線的環境下瀏覽。

---

## 📄 Pages｜頁面說明

| File | Description |
|---|---|
| `index.html` | 首頁、最新消息、重要公告、圖片輪播與快速連結 |
| `school-profile.html` | 學校介紹、校徽校訓、校園環境與影音 |
| `administrative-offices.html` | 行政單位與聯絡資訊 |
| `new-students.html` | 新生重要時程及入學相關資訊 |
| `academic-calendar.html` | 學校行事曆、PDF 文件與 Google Calendar |

---

## 🎨 UI / UX Design

網站加入多種視覺及互動設計，例如：

- Hover 動畫效果
- Fade-in 動畫
- 圖片浮動效果
- 公告卡片動畫
- Sticky Navigation
- 多層式 Drop-down Menu
- Smooth Scroll
- Responsive Grid Layout
- Dialog 搜尋結果視窗

透過這些設計提升網站的視覺效果以及資訊瀏覽體驗。

---
