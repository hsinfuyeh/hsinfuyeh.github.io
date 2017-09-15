---
layout: post
title:  "Google Analytics Note 2"
date:   2017-09-11 16:19:00 +0800
categories: Google Analytics
---
<h3>目標對象(Audience)</h3>
{% highlight ruby %}{% endhighlight %}
<h4>總覽(Overview)</h4>
<h4>活躍使用者(Active Users)</h4>
<h4>效期價值(Lifetime Value)</h4>
<h4>同類群組分析(Cohort Analysis)</h4>
<h4>使用者多層檢視(User Explorer)</h4>
<h4>客層(Demographics)－資料來自第三方的DoubleClick Cookies，因此analytics.js及ga.js均不會收集「客層、興趣」</h4>
{% highlight ruby %}如遇收集特定網頁的客層資料需要在GATC中加入ga('require', 'displayfeatures');。
＊置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　總覽(Overview)<br>
　　年齡層(Age)<br>
　　性別(Gender)<br>
<h4>興趣(Interests)－收集資料方式與客層相同</h4>
　　總覽(Overview)<br>
　　與興趣相似類別(Affinity Categories)<br>
　　潛在買家區隔(In-Market Segments)<br>
　　其他類別(Other Categories)<br>
<h4>地理區域(Geo)</h4>
　　語言(Language)<br>
　　地區(Location)<br>
<h4>行為(Behaviour)</h4>
　　新訪客與回訪者(New vs. Returning)<br>
　　頻率及回訪率(Frequency & Recency)<br>
　　主動參與(Engagement)<br>
　　工作階段品質(Session Quality)<br>
<h4>技術(Technology)</h4>
　　瀏覽器和作業系統(Browser & OS)<br>
　　聯播網(Network)<br>
<h4>行動裝置(Mobile)</h4>
　　總覽(Overview)<br>
　　裝置(Devices)<br>
<h4>自訂(Custom)－透過_utmv cookies達成</h4>
　　自訂變數(Custom Variables): 
{% highlight ruby %}在GATC中加入ga('set', 'dimension1', 'Test');。
＊置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　使用者定義(User-Defined)<br>
<h4>基準化(Benchmarketing)</h4>
　　頻道(Channels)<br>
　　地區(Location)<br>
　　裝置(Devices)<br>
<h4>使用者流程(Users Flow)</h4>


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>

＊DoubleClick: 隸屬於Google旗下的廣告推播服務，簡化規劃、投放、指定目標、放送、最佳化和產生報表等流程。<br>


