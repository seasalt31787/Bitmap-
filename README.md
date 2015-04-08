# Bitmap 作業報告
資訊之芽
sprout AT csie.ntu.edu.tw

## 簡介

本次作業我實作了 Sobel filter。
但是因為從來沒接觸過這個東西，所以到處私好友FB求救，結果才發現比想像中的簡單^^

## 實作方法與結果(+遇到的困難)
### Sobel Filter

Sobel filter 實作的結果如下圖。最左邊是原始圖片，經過 Sobel filter 運算的結果如右邊。

![Before Sobel Filter](http://tw-csie-sprout.github.io/programming15spring/pages/uploads/images/homework-bmp/flower_before.jpg) ![After Sobel Filter](http://tw-csie-sprout.github.io/programming15spring/pages/uploads/images/homework-bmp/flower_after.jpg)

當初先是Dev c++出現了小問題(無法編譯+執行)，沒想到還傻傻上社團去問問題，結果重開Dev c++就解決了。

![](https://imagizer.imageshack.us/v2/473x174q90/540/eHcNpc.png)

之後寫完執行後發現跟某位同學出現一樣狀況 圖片呈壞掉電視機樣

![](https://imagizer.imageshack.us/v2/300x300q90/661/UCOapu.png)

再來慢慢爬文
發現老師講了這2句話
1.新的canvas的值是舊的canvas的值套用的結果
不是新的canvas的值套用的結果
2.用舊的值全部算完新的值以後再把它寫回去

朋友也跟我說"不要邊運算邊蓋"(因為我跟他講我只會把舊的值蓋掉)，然後我想了一下才通。

## 結論

在本次作業中，Sobel filter 能夠計算出圖案大致的邊框。因為算出來有雜訊，我們可以把太維微細的變化過濾掉。


