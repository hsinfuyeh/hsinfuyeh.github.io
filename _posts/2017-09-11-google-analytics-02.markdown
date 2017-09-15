---
layout: post
title:  "Google Analytics Note 2"
date:   2017-09-11 16:19:00 +0800
categories: jekyll update
---
<h3>目標對象(Audience)</h3>
{% highlight ruby %}{% endhighlight %}
．<bold>總覽(Overview)</bold><br>
．<bold>活躍使用者(Active Users)</bold><br>
．<bold>效期價值(Lifetime Value)</bold><br>
．<bold>同類群組分析(Cohort Analysis)</bold><br>
．<bold>使用者多層檢視(User Explorer)</bold><br>
．<bold>客層(Demographics)</bold>－資料來自第三方的DoubleClick Cookies，因此analytics.js及ga.js均不會收集「客層、興趣」。
　　　　　　　　　　　{% highlight ruby %}如遇收集特定網頁的客層資料需要在GATC中加入ga('require', 'displayfeatures');。
＊置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　總覽(Overview)<br>
　　年齡層(Age)<br>
　　性別(Gender)<br>
．<bold>興趣(Interests)</bold>－收集資料方式與客層相同<br>
　　總覽(Overview)<br>
　　與興趣相似類別(Affinity Categories)<br>
　　潛在買家區隔(In-Market Segments)<br>
　　其他類別(Other Categories)<br>
．<bold>地理區域(Geo)</bold><br>
　　語言(Language)<br>
　　地區(Location)<br>
．<bold>行為(Behaviour)</bold><br>
　　新訪客與回訪者(New vs. Returning)<br>
　　頻率及回訪率(Frequency & Recency)<br>
　　主動參與(Engagement)<br>
　　工作階段品質(Session Quality)<br>
．<bold>技術(Technology)</bold><br>
　　瀏覽器和作業系統(Browser & OS)<br>
　　聯播網(Network)<br>
．<bold>行動裝置(Mobile)</bold><br>
　　總覽(Overview)<br>
　　裝置(Devices)<br>
．<bold>自訂(Custom)</bold>－透過_utmv cookies達成。<br>
　　自訂變數(Custom Variables)－{% highlight ruby %}在GATC中加入ga('set', 'dimension1', 'Test');。
＊置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　使用者定義(User-Defined)<br>
．<bold>基準化(Benchmarketing)</bold><br>
　　頻道(Channels)<br>
　　地區(Location)<br>
　　裝置(Devices)<br>
．<bold>使用者流程(Users Flow)</bold><br>


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>

＊DoubleClick: 隸屬於Google旗下的廣告推播服務，簡化規劃、投放、指定目標、放送、最佳化和產生報表等流程。<br>


