---
layout: post
title:  "Google Analytics Note 5"
date:   2017-09-14 16:13:00 +0800
categories: Google Analytics
---
<h3>轉換(Conversions)</h3>
{% highlight ruby %}{% endhighlight %}
<h4>目標(Goals): Admin→View→Goals→+New Goal</h4>
{% highlight ruby %}類型包含目標網址(Destination)、時間長度(Duration)、單次工作階段頁數/畫面數(Pages/Screens per session)及事件(Event){% endhighlight %}
　　總覽(Overview)<br>
　　目標網址(Goal URLs)<br>
　　反轉目標路徑(Reverse Goal Path)<br>
　　程序視覺呈現(Funnel Visualisation)<br>
　　目標流程(Goal Flow)<br>
　　智慧目標(Smart Goals)<br>
<h4>電子商務(E-commerce): 需自行加入程式碼，且須至於ga('send', 'pageview')之後</h4>
　　[Link][E-commerce]<br>
　　總覽(Overview)<br>
　　購物行為(Shopping Behaviour): 查看購買程序各階段的工作階段數<br>
　　結帳行為(Checkout Behaviour): 使用者完成結帳程序的順利程度<br>
　　產品業績(Product Performance): 依據設定的產品名稱來顯示其銷售狀況<br>
　　銷售業績(Sales Performance): 以銷售日期為預設維度，呈現不同日期間的收益<br>
　　產品資訊成效(Product List Performance)<br>
<h4>行銷(Marketing)</h4>
　　內部宣傳(Internal Promotion)<br>
　　訂單優待券(Order Coupon)<br>
　　產品優待券(Product Coupon)<br>
　　聯盟代碼(Affiliate Code)<br>
<h4>多管道程序(Multi-Channel Funnels)</h4>
　　總覽(Overview)<br>
　　輔助轉換(Assisted Coversions): 轉換前訪客與網站之間的任何非最終互動<br>
　　最佳轉換路徑(Top Conversion Paths): 
　　　　1.多媒體廣告(Display): 透過千次曝光出價(CPM, Cost-per-thousand-impressions)<br>
　　　　2.付費搜尋(Paid Search): 藉由單次點擊出價(CPC, Cost-per-click)或每次點擊出價(Pay-per-click, PPC)<br>
　　　　3.其他廣告(Other Advertising): 媒介標記為「cpc」、「ppc」、「cpm」、「cpv」、「cpa」、「cpp」或「affiliate」(不含付費搜尋) 的工作階段<br>
　　　　4.隨機搜尋(Organic Search)<br>
　　　　5.社交網路(Social Network)<br>
　　　　6.參照連結網址(Referral): 由非社交網路網站所帶來的流量<br>
　　　　7.電子郵件(Email)<br>
　　　　8.直接(Direct)<br>
　　轉換耗時(Time Lag)<br>
　　路徑長度(Path Length)<br>
<h4>功勞歸屬(Attribution)</h4>
　　模式比較工具(Model Comparison Tool): 
　　　　1.最終互動(Last Interaction): 完成目標轉換前的最終互動(Direct)<br>
　　　　2.上次非直接造訪點擊(Last Non-Direct Click): 完成目標轉換前的最終互動，但非透過直接輸入方式(Email)<br>
　　　　3.對AdWords廣告的最終點擊(Last AdWords Click): 歸功於最後一則AdWords廣告<br>
　　　　4.最初互動(First Interaction): 訪客與網站最初互動(AdWords)<br>
　　　　5.線性(Linear): 將功勞均分給完成轉換前曾互動過的每一環節<br>
　　　　6.時間衰減(Time Decay)以距離轉換日期長短作為判斷依據，距離越近功勞越大<br>
　　　　7.根據排名(Position Based): 焦點置於最初與最終互動(80%=Paid Search and Direct, 20%= Social and Email)<br>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>

[E-commerce]:https://developers.google.com/analytics/devguides/collection/analyticsjs/ecommerce