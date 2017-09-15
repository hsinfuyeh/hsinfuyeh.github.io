---
layout: post
title:  "Google Analytics Note 3"
date:   2017-09-12 16:19:00 +0800
categories: jekyll update
---
<h3>客戶開發(Acquisition)</h3>
{% highlight ruby %}{% endhighlight %}
<h4>總覽(Overview)</h4>
<h4>所有流量(All Traffic)</h4>
　　頻道(Channels): 自訂新管道：Admin→View→Custom Channel Groupings<br>
　　樹狀圖(Treemaps): 主要指標(大小表示)、次要指標(顏色表示)、僅可顯示前15名。<br>
　　來源/媒介(Source/Medium)<br>
　　參照連結網址(Referrals)<br>
<h4>Adwords: 一個廣告活動可有多個廣告群組；一個廣告群組可有多個廣告</h4>
　　帳戶(Accounts)<br>
　　廣告活動(Campaigns)<br>
　　樹狀圖(Treemaps)<br>
　　網站連結(Sitelinks)<br>
　　出價調整幅度(Bid Adjustments)<br>
　　關鍵字(Keywords)<br>
　　搜尋查詢(Search Queries)<br>
　　時段(Hour of Day)<br>
　　最終到達網址(Final URLs)<br>
　　指定多媒體廣告聯播網(Display Targeting)<br>
　　影片廣告活動(Video Campaigns)<br>
　　購物廣告活動(Shopping Campaigns)<br>
<h4>搜尋引擎最佳化(Search Console): Admin→Property→Property Settings→Search Console Settings</h4>
　　到達網頁(Landing Pages)<br>
　　國家/地區(Countries)<br>
　　裝置(Devices)<br>
　　查詢(Queries)<br>
<h4>社交(Social)</h4>
　　總覽(Overview)<br>
　　社交網路參照連結網址(Newwork Refferrals)<br>
　　到達網頁(Landing Pages)<br>
　　轉換(Conversions)<br>
　　外掛程式(Plug-ins): [GATC][GA-Facebook-like-button]/[FB Code][FB-Code]<br>
　　使用者流程(Users Flow)<br>
<h4>廣告活動(Campaigns)</h4>
　　所有廣告活動(All Campaigns)<br>
　　　　1. 非Google所屬的廣告活動分析: 需於連結網址加入特定參數
{% highlight ruby %}"utm_source", "utm_medium", "utm_term", "utm_content"及"utm_campaign"{% endhighlight %}
　　　　　 網址生成器：[Link][URL-Builder]<br>
　　　　2. Google所屬的廣告活動分析<br>
　　付費關鍵字(Paid Keywords)<br>
　　隨機關鍵字(Organic Keywords)<br>
　　費用分析(Cost Analysis)<br>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>

[URL-Builder]:https://ga-dev-tools.appspot.com/campaign-url-builder
[GA-Facebook-like-button]:https://developers.google.com/analytics/devguides/collection/analyticsjs/social-interactions
[FB-Code]:https://developers.facebook.com/docs/plugins/like-button