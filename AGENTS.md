# 空氣和風（專案藍圖）

> 跨 Agent 通用專案藍圖。每個 session 先讀本檔＋`handoff.md`。

## 專案簡介

國小三年級自然「空氣和風」單元的全套教學資源：教案（docx）、21 頁簡報（pptx＋JPG）、教學網頁（簡報播放器／10 題測驗／5 部影片／抽籤／計時器）、30 題對戰題庫，已部署 GitHub Pages。

## 課程設定

| 項目 | 內容 |
|---|---|
| 年級 | 國小三年級（上學期） |
| 單元 | 第三單元 空氣和風 |
| 節數 | 3 節（120 分鐘） |
| 核心概念 | 空氣無所不在／佔有空間／沒有固定形狀／可壓縮／流動形成風／風向與風力／風的應用與安全 |

> ⚠️ 版本註記：南一 115 學年度三上第三單元為「認識動物」；「風與空氣」為翰林三上第三單元。本教材依「空氣和風」主題編寫，用語採國小自然共通概念，不綁定單一版本。

## 資料夾結構

```
115-1_三上自然_空氣和風/
├── AGENTS.md / handoff.md
├── 教案/教案_空氣和風.docx
├── 簡報/空氣和風_教學簡報.pptx
├── 教學網頁/           ← GitHub Pages 部署來源
│   ├── index.html
│   ├── battle.html / server.js / questions.json（答案檔，不部署）
│   ├── slides/slide01–21.jpg
│   ├── downloads/（教案、簡報）
│   └── media/（旁白動畫，尚未產出）
├── scripts/（content.py、build_docx.py、build_slides.py、build_battle.py、patch_site.py）
└── .github/workflows/pages.yml
```

## 上線

- 教學網頁：<https://rayilin.github.io/air-wind/>
- repo：<https://github.com/rayilin/air-wind>（公開）
- 答案檔已排除：`questions.json`、`server.js`、`start-battle.bat` 線上皆 404

## 工作約定

- 開工先讀 `handoff.md`，收工必更新
- 教材內容不編造：課綱代碼、影片連結都要驗證
- 學生資料只用座號；不把名單放進公開網站
- 所有回應與文件使用繁體中文
