# 將 AI 智慧博物館成果發布成外部可瀏覽網站

## 為什麼要改？
ChatGPT Space 頁面不是保證對所有外部訪客公開的網站。若訪客看到「Use Space with ChatGPT Plus」，就代表該訪客無法直接瀏覽你的 Space 內容。

這個資料夾已準備兩個不需要 ChatGPT 登入的靜態網頁：
- `index.html`：15 頁互動式教學簡報
- `wiki.html`：LLM Wiki 公開閱讀版摘要（含 7 篇來源、知識整合、術語、設計原則與實際查詢紀錄）

## 建議發布方式：Netlify Drop
1. 先把本 ZIP 解壓縮。
2. 開啟解壓縮後的 `AI智慧博物館_公開網站` 資料夾，確認裡面直接看得到 `index.html` 和 `wiki.html`。
3. 前往 https://app.netlify.com/drop 。
4. 依頁面指示登入或註冊（若要求）。
5. 將整個 `AI智慧博物館_公開網站` 資料夾拖曳到上傳區。
6. 發布完成後，Netlify 會提供一個以 `netlify.app` 結尾的網址。
7. 簡報網址是該網址根目錄；Wiki 公開摘要網址是在網址最後加上 `/wiki.html`。
8. 用瀏覽器的 InPrivate／無痕視窗，或請沒有登入你帳號的人測試。確認不用登入、不需要密碼就能打開。
9. 如果出現登入或密碼要求，請到 Netlify 專案的可見度／存取設定，確認網站設為 Public，且沒有啟用密碼保護或登入限制。

## 繳交時如何填連結？
- LLM Wiki 連結或成果：填 `https://你的網站.netlify.app/wiki.html`（公開閱讀版），並可在報告中補充原始 ChatGPT Space 是編輯工作區。
- 教學 HTML 簡報連結：填 `https://你的網站.netlify.app/`。
- 不要把 ChatGPT Space 頁面連結當成「任何外部使用者都能開啟」的公開網址。

## 檢查清單
- [ ] 首頁簡報可開啟，沒有 ChatGPT 登入畫面
- [ ] 15 張投影片可翻頁
- [ ] 第 14 頁互動測驗可以作答
- [ ] 頁首「閱讀公開版 Wiki」可以開啟 wiki.html
- [ ] wiki.html 可看到 7 篇來源與實際查詢紀錄
- [ ] 無痕視窗可開啟簡報與 Wiki
