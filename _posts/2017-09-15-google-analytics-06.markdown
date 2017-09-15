---
layout: post
title:  "Google Analytics Note 6"
date:   2017-09-15 16:27:00 +0800
categories: jekyll update
---
<h3>管理介面(Admin)</h3>
{% highlight ruby %}{% endhighlight %}
<h4>帳戶(Account)</h4>
　　帳戶設定(Account Settings)<br>
　　使用者管理(User Management)<br>
　　所有篩選器(All Filters)<br>
　　變更紀錄(Change History)<br>
　　垃圾桶(Rubbish Bin)<br>
<h4>資源(Property)</h4>
　　資源設定(Property Settings)<br>
　　　　＊資源匹配次數(Property Hit Volume): 免費版每月上限1千萬筆資料；付費版每月上限10億筆資料<br>
　　　　＊網頁活動分析(In-Page Analytics): 使用加強連結歸屬，需手動於來源網頁及目標網頁修改GATC<br>
{% highlight ruby %}ga('require', 'linkid', 'linkid.js'){% endhighlight %}
　　使用者管理(User Management)<br>
　　追蹤資訊(Tracking Info)<br>
<h5>產品連結(Product Linking)</h5>
　　　　AdWords連結(AdWords Linking)<br>
　　　　AdSense連結(AdSense Linking)<br>
　　　　Ad Exchange連結(Ad Exchange Linking)<br>
　　　　所有產品(All Product)<br>
　　　　<br>
　　　　回傳(Postbacks)<br>
　　　　目標對象定義(Audience Definitions)<br>
　　　　　　1.目標對象: 需手動於來源網頁及目標網頁修改GATC
{% highlight ruby %}ga('require', 'displayfeatures'){% endhighlight %}
　　　　　　2.動態屬性<br>
　　　　自訂定義(Custom Definitions)<br>
　　　　資料匯入(Data Import)<br>
<h4>資料檢視(View)</h4>
　　檢視設定(View Settings)<br>
　　使用者管理(User Management)<br>
　　目標(Goals)<br>
　　內容分組(Content Grouping)<br>
　　　　1. 按追蹤程式碼分組(Group by Tracking Code): [Link][Group-by-TC]<br>
　　　　2. 使用資訊擷取的群組(Group Using Extraction): [Link][Group-Using-Extraction]<br>
　　　　3. 使用規則定義進行分組(Group Using Rule Definitions):<br>
　　篩選器(Filters): 主要功能為將不需要的流量排除<br>
　　頻道設定(Channel Settings)<br>
　　電子商務設定(E-commerce Settings)<br>
　　計算過的指標(Calculated Metrics): 在GA內自訂算式進行跨報表的計算，並呈現於資訊主頁或自訂報表<br>
　　<br>
<h5>個人工具與資源(Personal Tools & Assets)</h5>
　　　　區隔(Segments): 從已收集的流量資料中取用所需的資料並排除不需要的<br>
　　　　註解(Annotations): 任何擁有權限者皆可於任意報表加註其意見與想法<br>
　　　　歸屬模式(Attribution Models)<br>
　　　　自訂管道分組(Custom Channel Groupings)<br>
　　　　自訂快訊(Custom Alerts)<br>
　　　　定期寄送的電子郵件(Scheduled Emails)<br>
　　　　捷徑(Shortcuts)<br>
　　　　共用資源(Share Assets)<br>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>

＊篩選器(Filter) v.s 區隔(Segments): 篩選器是尚未開始收集資料前便已排除；區隔是資料收集後再加以處理。

[Group-by-TC]:https://support.google.com/analytics/answer/2853546?hl=zh-Hant
[Group-Using-Extraction]:https://support.google.com/analytics/answer/1034324?hl=zh-Hant