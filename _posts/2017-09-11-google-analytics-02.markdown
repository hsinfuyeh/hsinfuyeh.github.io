---
layout: post
title:  "Google Analytics Note 2"
date:   2017-09-11 16:19:00 +0800
categories: jekyll update
---
<h3>目標對象(Audience)</h3>
{% highlight ruby %}{% endhighlight %}
．總覽(Overview)
．活躍使用者(Active Users)
．效期價值(Lifetime Value)
．同類群組分析(Cohort Analysis)
．使用者多層檢視(User Explorer)
．客層(Demographics)－資料室來自第三方的DoubleClick Cookies，因此analytics.js及ga.js均不會收集「客層、興趣」。如遇收集特定網頁的客層資料需要{% highlight ruby %}在GATC中加入ga('require', 'displayfeatures');{% endhighlight %}。*置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。
　　總覽(Overview)
　　年齡層(Age)
　　性別(Gender)
．興趣(Interests)－收集資料方式與客層相同
　　總覽(Overview)
　　與興趣相似類別(Affinity Categories)
　　潛在買家區隔(In-Market Segments)
　　其他類別(Other Categories)
．地理區域(Geo)
　　語言(Language)
　　地區(Location)
．行為(Behaviour)
　　新訪客與回訪者(New vs. Returning)
　　頻率及回訪率(Frequency & Recency)
　　主動參與(Engagement)
　　工作階段品質(Session Quality)
．技術(Technology)
　　瀏覽器和作業系統(Browser & OS)
　　聯播網(Network)
．行動裝置(Mobile)
　　總覽(Overview)
　　裝置(Devices)
．自訂(Custom)－透過_utmv cookies達成。
　　自訂變數(Custom Variables)－{% highlight ruby %}在GATC中加入ga('set', 'dimension1', 'Test');{% endhighlight %}。*置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。
　　使用者定義(User-Defined)
．基準化(Benchmarketing)
．使用者流程(Users Flow)


-----------------------------------------------------------------------
*DoubleClick: 隸屬於Google旗下的廣告推播服務，簡化規劃、投放、指定目標、放送、最佳化和產生報表等流程。


