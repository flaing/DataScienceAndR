# DataScienceAndR

這個Repository主要是為了準備我在臺大的資料科學課程，幫陳老師講的兩堂R 的課程。

第一堂課程的主軸，是要介紹R 語言的背景、特色，以及簡易的環境設定。目標是希望同學在聽完之後，可以開始利用swirl來自學所有R 的基礎。

第二堂課程的主軸，是要介紹R 在Data Mining相關的功能。課程內容希望是涉獵一些我做過的專案，並且介紹一些R 在clustering、frequency pattern mining、
和recommendation上的一些套件。

由於出自R 社群的緣故，所有的內容我都想公佈在這個repository，以創用CC釋出。 


# 設定環境

## Windows

目前swirl沒辦法在windows上正常顯示中文（ https://github.com/swirldev/swirl/pull/300 已經提交，等待swirl的開發者處理中），
所以請暫時先安裝我修改過的版本：

```r
install.packages('swirl', repos = 'http://taiwanrusergroup.github.io/R')
```

## Mac, Ubuntu

請直接安裝CRAN上的swirl

```r
install.packages('swirl')
```


# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/tw/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/tw/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Data Science and R</span>由<a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/wush978/DataScienceAndR" property="cc:attributionName" rel="cc:attributionURL">Wush Wu</a>製作，以<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/tw/">創用CC 姓名標示-相同方式分享 3.0 台灣 授權條款</a>釋出。
