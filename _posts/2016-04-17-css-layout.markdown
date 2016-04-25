---
layout: post
title:  "CSS Layout Notes"
date:   2016-04-17 20:19:22 +0800
categories: jekyll update
---
<h3>stick the footer to the bottom</h3>
{% highlight ruby %}
min-height: calc(100vh - (footer's total height)px);
{% endhighlight %}

<h3>clearfix</h3>
three ways to solve the collapsing problem
1) Give it a height
<br>
2) `overflow: hidden;`
<br>
3) clearfix (the properest way)
{% highlight ruby %}
.clearfix::after {
  content: "";
  display: table;
  clear: both;
}
{% endhighlight %}

<h3>Positioning the caption over the img</h3>
．Positioning the figcaption element absolute<br>
．Set the parent figure element as the relative positioning context

<h3>How to make heading stay fixed</h3>
{% highlight ruby %}
body {
  padding-top: ##px;
}
(##: the height of the heading)

.main-header {
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1;
}
(z-index: won't work if there's on position value )
{% endhighlight %}
