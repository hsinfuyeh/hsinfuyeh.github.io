---
layout: post
title:  "Google Analytics Note 2"
date:   2017-09-11 16:19:00 +0800
categories: jekyll update
---
<h3>目標對象(Audience)</h3>
{% highlight ruby %}{% endhighlight %}
．總覽(Overview)<br>
．活躍使用者(Active Users)<br>
．效期價值(Lifetime Value)<br>
．同類群組分析(Cohort Analysis)<br>
．使用者多層檢視(User Explorer)<br>
．客層(Demographics)－資料室來自第三方的DoubleClick Cookies，因此analytics.js及ga.js均不會收集「客層、興趣」。
　　　　　　　　　　　{% highlight ruby %}如遇收集特定網頁的客層資料需要在GATC中加入ga('require', 'displayfeatures');。
*置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　總覽(Overview)<br>
　　年齡層(Age)<br>
　　性別(Gender)<br>
．興趣(Interests)－收集資料方式與客層相同<br>
　　總覽(Overview)<br>
　　與興趣相似類別(Affinity Categories)<br>
　　潛在買家區隔(In-Market Segments)<br>
　　其他類別(Other Categories)<br>
．地理區域(Geo)<br>
　　語言(Language)<br>
　　地區(Location)<br>
．行為(Behaviour)<br>
　　新訪客與回訪者(New vs. Returning)<br>
　　頻率及回訪率(Frequency & Recency)<br>
　　主動參與(Engagement)<br>
　　工作階段品質(Session Quality)<br>
．技術(Technology)<br>
　　瀏覽器和作業系統(Browser & OS)<br>
　　聯播網(Network)<br>
．行動裝置(Mobile)<br>
　　總覽(Overview)<br>
　　裝置(Devices)<br>
．自訂(Custom)－透過_utmv cookies達成。<br>
　　自訂變數(Custom Variables)－{% highlight ruby %}在GATC中加入ga('set', 'dimension1', 'Test');。
*置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　使用者定義(User-Defined)<br>
．基準化(Benchmarketing)<br>
　　頻道(Channels)<br>
　　地區(Location)<br>
　　裝置(Devices)<br>
．使用者流程(Users Flow)<br>


-----------------------------------------------------------------------<br>
*DoubleClick: 隸屬於Google旗下的廣告推播服務，簡化規劃、投放、指定目標、放送、最佳化和產生報表等流程。<br>


