關於 /src 的説明
================
### 子目錄的説明
<table>
<tbody><tr>
<td>/src/ptt_python</td>
<td>ptt 的 python 版的資料與資料處理的程式碼(王凱弘)</td>
</tr>
<tr>
<td>/src/ptt_r</td>
<td>ptt 的 R 版的資料與資料處理的程式碼(石晴方)</td>
</tr>
<tr>
<td>/src/reddit_python</td>
<td>reddit 的 python 版的資料與資料處理的程式碼(張鈺琳)</td>
</tr>
<tr>
<td>/src/reddit_r</td>
<td>reddit 的R 版的資料與資料處理的程式碼(張飛揚)</td>
</tr>
</tbody>
</table>
### 資料的獲取和處理方式
- 獲取: 在 R 環境下，分別使用 PTTmineR (用於爬取 ptt)和 rreddit (用於爬取 reddit)獲取貼文資料
- 處理: 使用 dplyr, tidytext, stringr 等處理資料，使用 ggplot2, wordcloud2 等製作展示圖像
