# Reel Studio 網頁工單

史傳奇短影片工作室的工單前台（單一靜態 HTML，GitHub Pages 發布）。

- 使用者把素材與口白放進 Google Drive 資料夾，在網頁填工單後送出。
- 網頁把工單 JSON POST 到 Grok Bot routine 的 webhook；webhook 網址與金鑰只存在使用者瀏覽器的 localStorage，**不在這個 repo 裡**。
- 送出失敗時，網頁提供「複製工單內容」，貼到與史傳奇的聊天即可。
- 網頁本身不處理、不上傳任何影片。示範截圖只用無人物的產品畫面。
