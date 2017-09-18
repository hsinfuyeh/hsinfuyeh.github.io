---
layout: post
title:  "Google Analytics Note 2"
date:   2017-09-11 16:19:00 +0800
categories: Google Analytics
---
<h3>目標對象(Audience)</h3>
{% highlight ruby %}{% endhighlight %}
<h4>總覽(Overview)</h4>
<h4>活躍使用者(Active Users): 一段時間內曾造訪網站的不重複訪客數</h4>
<h4>效期價值(Lifetime Value)</h4>
<h4>同類群組分析(Cohort Analysis):將具共同特質訪客予以歸納分類，觀察其行為特性與投注在其身上的行銷特效</h4>
<h4>使用者多層檢視(User Explorer)</h4>
<h4>客層(Demographics)－資料來自第三方的DoubleClick Cookies，因此analytics.js及ga.js均不會收集「客層、興趣」</h4>
{% highlight ruby %}如欲收集特定網頁的客層資料需要在GATC中加入ga('require', 'displayfeatures');。
＊置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　總覽(Overview)<br>
　　年齡層(Age)<br>
　　性別(Gender)<br>
<h4>興趣(Interests)－收集資料方式與客層相同</h4>
　　總覽(Overview)<br>
　　與興趣相似類別(Affinity Categories): 訪客對於在多媒體廣告聯播網上的不同類型網站感興趣程度<br>
　　潛在買家區隔(In-Market Segments): 對某種類型產品有購買意願<br>
　　其他類別(Other Categories): <br>
<h4>地理區域(Geo)</h4>
　　語言(Language)<br>
　　地區(Location)<br>
<h4>行為(Behaviour)</h4>
　　新訪客與回訪者(New vs. Returning)<br>
　　頻率及回訪率(Frequency & Recency): 訪客再次與網站互動所需間格時間<br>
　　主動參與(Engagement): 訪客造訪網站的工作階段時間長度與瀏覽頁數<br>
　　工作階段品質(Session Quality)<br>
<h4>技術(Technology)</h4>
　　瀏覽器和作業系統(Browser & OS)<br>
　　聯播網(Network): 訪客所使用的網際網路服務供應商<br>
<h4>行動裝置(Mobile)</h4>
　　總覽(Overview)<br>
　　裝置(Devices)<br>
<h4>自訂(Custom)－透過_utmv cookies達成</h4>
　　自訂變數(Custom Variables): 
{% highlight ruby %}在GATC中加入ga('set', 'dimension1', 'Test');。
＊置於ga('create', 'UA-xxxxxx-xx', 'example.com');及ga('send', 'pageview');之間。{% endhighlight %}<br>
　　使用者定義(User-Defined)<br>
<h4>基準化(Benchmarketing)</h4>
　　頻道(Channels): 七種預設管道分組－隨機搜尋(Organic Search)、參照連結網址(Referral)、直接(Direct)、社交(Social)、多媒體廣告(Display)、付費關鍵字(Paid Search)、電子郵件(Email)<br>
　　地區(Location)<br>
　　裝置(Devices)<br>
<h4>使用者流程(Users Flow)</h4>


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>

＊DoubleClick: 隸屬於Google旗下的廣告推播服務，簡化規劃、投放、指定目標、放送、最佳化和產生報表等流程。<br>


