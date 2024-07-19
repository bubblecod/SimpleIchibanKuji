# SimpleIchibanKuji

[English](#english) | [中文](#中文)

### What is Simple IchibanKuji?<a id='english'></a>
This is a very simple and intuitive IchibanKuji tool that you can use to create your own custom IchibanKuji lottery. Every function is ready to go and free to use!

### How to use Simple IchibanKuji

You can use it in the [DEMO](https://tool.bucod.me/ichibankuji_demo/ "DEMO") environment, or you can just download this repo and run it on your own computer locally and [customize](#paras) it as needs. However, please note:
- You are not able to change and save parameters in incognito mode.
- You are not able to save the progress of lottery in the DEMO environment.
- You are not able to change icons or animations in the DEMO environment.
- You can use the browser's zoom function (Ctrl + wheel) to adjust the display ratio of the IchibanKuji page.

### How to set parameters<a id='paras'></a>
Level | Parameter | Description
------------- | ------------- | -------------
(root) | title | Set title property for the tab of page
(root) | name | Showing the name on top of the IchibanKuji panel
content | height | Rows of IchibanKuji, shows as </br>1</br>2</br>3</br>...
content | width | Columns of IchibanKuji, shows as ABC...
content | prize | Prizes that going randomly into IchibanKuji (within the range of height x width). Each character turns into one prize.
content | counter | Define which type(s) of prize should be counted
content | big_prize | Define which type(s) of prize as special prize
content | big_prize_color | background color for big/special prize (deg of hue)
anime | win | Define the winning anime shows when the big/special prize reveals (relative path or URL)
anime | troll | Define the fake winning anime shows when the normal prize reveals (relative path or URL)
anime | anime_time | Time of anime (in millisecond)
style | main | main color
style | secondary | secondary color
style | highlight | highlight background color when hover over
style | background1 | outter background color
style | background2 | inner background color
style | fontcolor1 | outter font color
style | fontcolor2 | inner font color
style | icon | icon for hidden prizes of IchibanKuji (relative path or URL)


### Others

----

### 什麼是Simple IchibanKuji ?<a id='中文'></a>
這是一個非常簡單直覺的一番賞小工具，你可以進行簡單的客製化調整，並利用它來進行抽獎遊戲，一切都是免費的!

### 如何使用Simple IchibanKuji ?
你可以在[DEMO](https://tool.bucod.me/ichibankuji_demo/ "DEMO")環境中使用，你也可以打包下載這個repo，並在自己的電腦上執行，並根據自己的需要調整[設定](#設定)，但請注意：
- 你無法在無痕模式中使用進階設定
- 你無法在DEMO環境中使用儲存功能
- 你無法在DEMO環境中更改圖示、動畫
- 你可以使用瀏覽器的縮放功能(Ctrl + 滾輪)來調整一番賞頁面的縮放比例

### 如何設定參數 ?<a id='設定'></a>
層級 | 參數名稱 | 說明
------------- | ------------- | -------------
(root) | title | 一番賞分頁的瀏覽器頁籤名稱
(root) | name | 一番賞工具的標題
content | height | 橫排(高)的數量，對應為:</br>1</br>2</br>3</br>...
content | width | 直排(寬)的數量，，對應為:ABC...
content | prize | 獎項，一個字元代表一個獎項，隨機分配於高x寬的範圍中
content | counter | 開獎計數器，可以無/部分/全部獎項計數，計數器順序同設定值順序
content | big_prize | 定義為大獎的獎項
content | big_prize_color | 大獎底色(色調偏移，單位為deg)
anime | win | 大獎動畫 (相對路徑或URL)
anime | troll | 欺騙動畫 (相對路徑或URL)
anime | anime_time | 動畫持續時間(毫秒)
style | main | 主色調
style | secondary | 副色調
style | highlight | 懸停時背景色
style | background1 | 主背景色
style | background2 | 副背景色
style | fontcolor1 | 主文字顏色
style | fontcolor2 | 副文字顏色
style | icon | 一番賞圖示 (相對路徑或URL)

### 其他
