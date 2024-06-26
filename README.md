# cycu-linebot-final

CYCU IM 1122 聊天機器人實作 Final Project
開發環境與技術：Anaconda、 LineBot、 Django 4.1 。

### 主題：準備面試的考生聊天機器人
---
### 圖文選單功能介紹

1. **面試建議：** 
   1. 利用快速回覆選單 `QuickReply` 選擇學院
   2. 利用影像地圖訊息 `ImagemapSendMessage` 選擇對應科系
   3. 查詢該科系在網路上的面試建議。
   4. 資料來源為網路資料與團隊成員面試心得統整。
2. **服裝規定：** 根據性別或是中性打扮提供面試時的服裝建議。
3. **必修科目：** 
   1. 利用快速回覆選單 `QuickReply` 選擇查詢學院
   2. 利用影像地圖訊息 `ImagemapSendMessage` 選擇對應科系
   3. 回傳中原大學 112 學年度各科系必修科目表、英文畢業門檻。
4. **生活機能：** 使用彈性訊息 `BubbleContainer` 提供附近飲食、交通方式、電話、住宿費用等快速資訊查詢。
5. **建立面試行事曆：** 
   1. 串接 Google 日曆 API 。
   2. 輸入面試開始/結束時間、地點、描述，之後在 Google 日曆建立相對應的活動事件。
6. **學校快速連結：** 使用樣板訊息 `TemplateSendMessage`提供方便查詢學校各處室的連結。


[Google Calendar API with Python](https://developers.google.com/calendar/api/quickstart/python?hl=zh_TW)
   
[Line Bot Messaging API overview](https://developers.line.biz/en/docs/messaging-api/overview/)