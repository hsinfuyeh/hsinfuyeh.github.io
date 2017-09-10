---
layout: post
title:  "Google Analytics Note 1"
date:   2017-09-10 16:38:22 +0800
categories: jekyll update
---
<h3></h3>
{% highlight ruby %}{% endhighlight %}
1. GA支援3種API(Application Programming Interface): 收集、管理、資料匯出
2. GA的Tracking Code將毫無作用如果瀏覽器停用Active Scripting
3. 瀏覽器閒置超過30分鐘，GA便會將再次地造訪行為紀錄為新的工作階段
4. GA使用七種Cookies: _utma, _utmb, _utmc, _utmv. utmx/_utmxx, _utmz, _ga
5. _utma: 辨識新訪客或是回訪者<br>
  _utmb: 紀錄訪客在網站上的網頁瀏覽情況。屬於暫時性Cookies，存續時間僅30分鐘。<br>
  _utmc: 與_utmb相似，GA目前已不使用_utmc。
  _utmv: 透過自訂變數，針對不同群組的訪客進行區隔分析。屬於持續性Cookies，存續時間可達2年。<br>
  _utmx/_utmxx: 主要用於測試不同版本網頁實驗的狀況(A/B Test)<br>
  _utmz: 儲存流量來源與活動相關資訊，屬於持續性Cookies，存續時間為6個月。<br>
  _ga: 屬於持續型Cookies，存續時間為2年。
6. 1 Gmail Account > 100 GA Accounts > 50 Properties > 25 views
7. 

