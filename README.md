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

當初先是Dev c++出現了小問題(無法編譯+執行)，沒想到還傻傻上去問問題，結果重開Dev c++就解決了。

(https://drive.google.com/drive/folders/0B20PbhQDsshxfnhGdDJPR0V2RldBdDhIMDlzR1BWT3RTc2VjYy1ndGlwcW9GajBYWG1LcDQ)




## 結論

在本次作業中，Sobel filter 能夠計算出圖案大致的邊框。因為算出來有雜訊，我們可以把太維微細的變化過濾掉。

產生隨機圖片時，我發現透過疊加顏色而非直接設定顏色的方式，可以讓圖片的顏色看起來比較連續，不會有突兀的效果。同時這樣產生出來的圖片也有半透明的效果。隨機貼上素材圖時，則可以依層次調整亮度，也可以隨機修改圖片的縮放、旋轉角度等。
