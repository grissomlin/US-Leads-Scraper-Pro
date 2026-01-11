# 🗺️ US-Leads-Scraper-Pro

**An AI-powered, zero-cost B2B lead generation tool for the US market.**
**一款基於 AI 驅動、零成本的美國市場 B2B 獲客工具。**

---

## 📖 Project Overview / 專案簡介

Inspired by high-priced commercial software seen on social media (TikTok), this project explores how to use AI (Python + Selenium) to build a professional-grade Google Maps scraper and dashboard. Unlike expensive official APIs, this **Scraper Version** provides a zero-threshold entry for SOHO and SMEs to automate their business development process on Google Colab.

受到抖音上昂貴商業軟體的啟發，本專案展示了如何利用 AI 輔助開發（Python + Selenium）構建專業級的 Google Maps 爬蟲與儀表板。與門檻較高的官方 API 不同，此**爬蟲版**為外貿 SOHO 與中小企業提供了一個零門檻的選擇，讓您在 Google Colab 上實現開發流程自動化。

---

## 🔗 Tutorial & Documentation / 教學與操作說明

Detailed step-by-step guides are available on **Vocus (方格子)**. It is highly recommended to read these before starting:
詳細的圖文教學已發布於 **方格子 (Vocus)**，強烈建議開始前先閱讀：

1.  **Operation Guide / 操作說明篇** 👉 [【外貿自動化】零成本開發美國獲客程式：儀表板操作說明](https://vocus.cc/article/6962f14cfd89780001b5f2ea)
2.  **Deployment Guide / 安裝部署篇** 👉 [【安裝部署篇】5 分鐘啟動您的雲端獲客工廠](https://vocus.cc/article/6962f9e1fd89780001b81217)

---

## ✨ Key Features / 核心功能

* **Smart Geographic Targeting**: Two-stage selection (State -> Zip Code) using the SimpleMaps database.
    **精準地理定位**：結合 SimpleMaps 數據庫，實現二階式（州別 -> 郵遞區號）篩選。
* **AI Outreach Automation**: Generate personalized B2B cold emails in English, Spanish, or French with one click.
    **AI 開發信自動化**：一鍵生成英、西、法三語個人化 B2B 開發信。
* **Real-time Dashboard**: Monitor scraping progress and manage leads via a Streamlit-based UI on Google Colab.
    **即時數據儀表板**：透過 Streamlit 介面監控進度並管理潛在客戶資料。
* **Multi-Platform Deep Research**: Quick links to Google, Yelp, IG, and FB for instant background checks.
    **多平台深度調查**：內建一鍵跳轉 Google, Yelp, IG, FB 按鈕，快速核實商家背景。
<img width="1838" height="854" alt="image" src="https://github.com/user-attachments/assets/e7ca27bb-cb2d-47da-9a50-d951fb58a4f9" />
<img width="1863" height="900" alt="image" src="https://github.com/user-attachments/assets/a08b861e-38b5-49ae-a554-23a616750b76" />
<img width="1464" height="843" alt="image" src="https://github.com/user-attachments/assets/10c95b01-c9c8-491c-a063-5f565044a563" />
<img width="1505" height="839" alt="image" src="https://github.com/user-attachments/assets/ea817097-fe00-40c9-a69a-61d059f48415" />
<img width="324" height="904" alt="image" src="https://github.com/user-attachments/assets/02453ba5-119f-46fe-8b5b-e7b9573aebf4" />


---

## 🚀 Quick Start / 快速上手

1.  **Download Database**: Obtain `simplemaps_uszips_basicv1.80.zip` from [SimpleMaps](https://simplemaps.com/data/us-zips).
    **下載數據庫**：從 SimpleMaps 取得美國郵編 ZIP 檔。
2.  **Upload to Colab**: Upload the ZIP file to the `/content` folder in Google Colab.
    **上傳至 Colab**：將 ZIP 檔直接拖曳上傳至 Colab 的 `/content` 資料夾。
3.  **Run Cells**: Execute the 5 core cells in order (Prompts -> Environment -> Worker -> App -> Tunnel).
    **依序執行**：按照順序執行五大核心儲存格。
4.  **Access Dashboard**: Click the `.trycloudflare.com` link provided in the last cell to open your interface.
    **啟動介面**：點擊最後一個 Cell 產出的 Cloudflare 連結即可進入操作面板。

---

## ⚠️ Important Notes / 重要提醒

* **Anti-Detection**: Do not scrape too many Zip codes at once to avoid IP temporary blocks.
    **頻率限制**：請勿一次掃描過多郵編，以免觸發防爬機制導致 IP 被暫時封鎖。
* **Data Persistence**: Files on Colab are temporary. Download your `leads.csv` regularly or integrate with Google Drive.
    **檔案保存**：Colab 空間是暫時性的，請定期下載 `leads.csv` 或自行掛載 Google Drive，否則重啟後檔案會消失。
* **Experimental Project**: This is a Scraper-based Demo version for educational and trial purposes.
    **專案性質**：本專案為基於爬蟲的 Demo 版本，旨在技術分享與實驗。

---

## ☕ Support the Project / 贊助與打賞

If you find this project helpful, feel free to support my work through the link below!
如果您覺得這個專案對您有幫助，歡迎透過下方連結贊助鼓勵！

👉 **[Donate on Vocus / 點我進行打賞](https://vocus.cc/pay/donate/606146a3fd89780001ba32e9?donateSourceType=article&donateSourceRefID=6962f9e1fd89780001b81217)**

---

## ⚖️ License
Distributed under the **MIT License**. See `LICENSE` for more information.
