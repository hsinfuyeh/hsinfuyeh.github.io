---
layout: post
title:  "Google Analytics Note 4"
date:   2017-09-13 18:27:00 +0800
categories: jekyll update
---
<h3>行為</h3>
{% highlight ruby %}{% endhighlight %}
．<bold>總覽(Overview)</bold><br>
．<bold>行為流程(Behaviour Flow)</bold><br>
．<bold>網站內容(Site Content)</bold>: 離開率v.s跳出率[Link][Exit-Bouncing]<br>
　　所有網頁(All Pages)<br>
　　內容深入分析(Content Drilldown)<br>
　　到達網頁(Landing Pages)<br>
　　離開網頁(Exit Pages)<br>
．<bold>網站速度(Site Speed)</bold><br>
　　總覽(Overview)<br>
　　網頁操作時間(Page Timings)<br>
　　速度建議(Speed Suggestions)<br>
　　使用者載入時間(User Timings): [Link][User-Timing]<br>
．<bold>站內搜尋(Site Search)</bold><br>
　　總覽(Overview)<br>
　　使用情況(Usage)<br>
　　搜尋字詞(Search Terms)<br>
　　搜尋網頁(Search Pages)<br>
．<bold>事件(Events)</bold>: 網站上被觸發的事物分兩類，事件及目標。事件－觸發之事物並未開啟新分頁。目標－觸發之事物開啟新分頁。<br>
　　總覽(Overview)<br>
　　熱門事件(Top Events)<br>
　　網頁(Pages): 事件觸發需加入程式碼<br>
{% highlight ruby %}<a href="example.com" onclick="ga('send', 'event', 'catagory', 'action', 'label', 'value')">title</a>{% endhighlight %}
send及event為告知GA目前將傳送事件、category: 事件類別、action: 事件動作、label: 活動標籤、value: 事件值(事件觸發所衍生的值)。<br>
＊或是可以將event改為pageview用虛擬網頁的方式，將點擊視為一個網頁瀏覽。<br>
　　事件流程(Events Flow)<br>
．<bold>發佈商(Publisher)</bold><br>
　　總覽(Overview)<br>
　　發佈商網頁(Publisher Pages)<br>
　　發佈商參照網址(Publisher Referrers)<br>
．<bold>實驗(Experiments)</bold><br>



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>

[Exit-Bouncing]:https://support.google.com/analytics/answer/2525491?hl=zh-Hant
[User-Timing]:https://developers.google.com/analytics/devguides/collection/analyticsjs/user-timings?hl=zh-tw