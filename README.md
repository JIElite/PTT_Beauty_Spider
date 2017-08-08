# PTT 表特版爬蟲圖片下載器[Deprecated]

## Project Status
This project is currently deprecated. Because of personal reason I may not maintain this project. If you're interesting in this kind of project, you can visit some fork version:

- [twtrubiks/PTT_Beauty_Spider](https://github.com/twtrubiks/PTT_Beauty_Spider)
- TBD (welcome to share other version for me)


## Issue & TODOs
- Using `requests` & `BeautifulSoup` to refactor Web Crawler.
- Using `Threading` or other asynchronized method to refactor download process, because file downloading is IO-bound process NOT CPU-bound process.


## 前言
這個 Program 是讓我用來練習爬蟲的基本概念，搭配多執行緒的使用 <br>
希望大家有建議或是批評都可以寫信給我，對我來說這是有效率的學習機會。
但是比較傾向自己改 code, 謝謝大家寶貴的意見! <br>

## 使用方法
```
$ python beauty_spider2.py 爬蟲起始的頁面 爬幾頁 推文多少以上 
```
如果要從最新頁面開始爬 第一個參數請填 -1 <br>
目前各種 bug 效能未優化。<br>
爬蟲是利用 PTT 網頁版，所以頁面以網頁版為標準。<br>
請參考： <br>
```
https://www.ptt.cc/bbs/Beauty/index.html
```

# 圖片說明
## 下載中
![alt tag](http://i.imgur.com/RoFrilx.jpg)<br>
## 下載完成
![alt tag](http://i.imgur.com/tLwYbj2.png) <br>
## 資料夾內部狀況
![alt tag](http://i.imgur.com/hu8MyIf.png) <br>
## 執行範例 
使用:
``` 
$ python beauty_spider2.py -1 100 100
```
![alt tag](http://i.imgur.com/xlkhW8B.png)
