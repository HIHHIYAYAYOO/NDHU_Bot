# NDHU_Bot
透過動態爬蟲實現網站自動點擊的工具

## 教學影片
[NDHU_Bot 教學連結](https://youtu.be/vXswUARh6iY)

## 安裝 Anaconda
1. 前往 [Anaconda官網](https://www.anaconda.com/download)。
2. 點擊 「Skip registration」。
3. 選擇符合你作業系統的版本。
4. 以 Windows 為例，點擊 Download。
5. 執行下載的exe檔。
6. 依序點擊 Next > I Agree > Next > Next > Install > Next > Finish。
7. 搜尋並開啟 Jupyter Notebook。
   
## 下載 NDHU_Bot
1. 前往 [NDHU_Bot](https://github.com/HIHHIYAYAYOO/NDHU_Bot/tree/main)。
2. 點擊「Code」> 「Download ZIP」。
3. 解壓縮 NDHU_Bot。
   
## 運行 NDHU_Bot
1. 於 Jupyter Notebook 中進入解壓縮後 NDHU_Bot 的目錄。
2. 開啟 NDHU_Bot.ipynb。
3. 運行第一個儲存格安裝'selenium'和'webdriver_manager'套件。
4. 運行第二個儲存格 導入套件。
5. 運行第三個儲存格 設定帳號、密碼以及點擊順序。
6. 運行第四個儲存格 開啟網站。
   * 如果沒成功跳出網站，更新 Chrome 版本(點擊右上角 ⁝ > 設定 > 關於 Chrome)，在運行一次。
   * 還是不行，需手動安裝 Chromedriver
   * 前往 [Chrome for Testing availability](https://googlechromelabs.github.io/chrome-for-testing/#stable)
   * 於Channel 中選擇 Stable
   * 複製符合您作業系統及 Chrome 版本的 chromedriver URL (注意不要複製到 chrome)
   * 貼上 URL 到搜尋欄，並下載 chromedriver 
   * 解壓縮 chromedriver-win64 資料夾
   * 將 chromedriver.exe 複製到 NDHU_Bot 的目錄下，在運行一次。
8. 運行第五個儲存格 自動點擊(可以提早運行)。

註: 記憶體大小及使用量會影響自動點擊速度

## 重要聲明
* 本工具為學術研究及交流而設計，旨在幫助使用者了解動態爬蟲技術及自動化操作的原理。
* 請勿將其用於任何違法或不當用途，例如干擾網路系統、作為外掛程式使用或冒用他人帳號。
