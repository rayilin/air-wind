# 交接檔（handoff.md）

> 接手前必讀；收工必更新。

## ⏯️ 目前做到哪

全套教材已產出並上線：教案 docx、21 頁簡報 pptx＋JPG、教學網頁（測驗／影片／工具）、30 題對戰題庫、GitHub Pages 部署完成。

## 🚦 目前狀態

- ✅ 教學網頁：<https://rayilin.github.io/air-wind/>（HTTP 200，21 張簡報圖正常）
- ✅ 教案：`教案/教案_空氣和風.docx`（13 節）
- ✅ 簡報：`簡報/空氣和風_教學簡報.pptx`（21 頁）＋`教學網頁/slides/*.jpg`
- ✅ 測驗 10 題（網頁內建）、對戰題庫 30 題（`questions.json`，未部署）
- ✅ `check_site.js` 通過；答案檔線上 404
- ❌ 4 段旁白動畫（`media/*.mp4`）尚未產出
- ❌ 對戰後端（Render）尚未部署，線上對戰區目前顯示離線說明

## ➡️ 下一步

1. 產 4 段旁白動畫（空氣佔空間／壓縮／流動成風／風向風力），放入 `教學網頁/media/`，並在 `SLIDES` 指定 video
2. 需要線上對戰時：部署 `battle-server.js` 到 Render，把網址填進 `battle-api.js` 再 push
3. 試教後調整題目難度與時間配當

## ⚠️ 注意事項

- `questions.json`、`server.js` 不可進公開站（workflow 已排除）
- 版本對照：南一 115 三上第三單元是「認識動物」；本教材依主題「空氣和風」編寫
- 簡報 JPG 由 `scripts/build_slides.py` 產生，改內容請改 `scripts/content.py` 後重跑

## 🕐 最後更新

- 時間：2026-11-15
- 更新者：OpenCode @ WIN-BV91KDG1BT8
- Git push：✅ 已推（rayilin/air-wind）
