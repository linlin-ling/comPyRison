## 關於 /src 的説明
==================
### 子目錄的説明
- /src/ptt_python:ptt的python版的資料與資料處理的程式碼(王凱弘)
- /src/ptt_r:ptt的R版的資料與資料處理的程式碼（石晴方）  
- /src/reddit_python:reddit的python版的資料與資料處理的程式碼（張鈺琳）  
- /src/reddit_r:reddit的R版的資料與資料處理的程式碼（張飛揚）  
### 資料的獲取和處理方式
- 獲取：在R環境下，分別使用PTTmineR（用於爬取ptt）和rreddit（用於爬取reddit）獲取貼文資料
- 處理：使用dplyr, tidytext, stringr等處理資料，使用ggplot2, wordcloud2等製作展示圖像
