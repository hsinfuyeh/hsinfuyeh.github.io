---
layout: post
title:  "CSS Syntax Notes"
date:   2016-03-31 20:17:00 +0800
categories: jekyll update
---
<h4>Back to Top</h4>
{% highlight ruby %}
<h1 id="top">Title</h1>
<a href="#top"><p>Back to Top</p></a>
{% endhighlight %}

<h4>padding</h4>
{% highlight ruby %}
padding: up right bottom left;
padding: up right and left bottom;
padding: up and bottom right and bottom;
{% endhighlight %}

<h4>background</h4>
{% highlight ruby %}
background: color url() repeat center(background-position) / cover(background-  size)
{% endhighlight %}

<h4>fix the collapse after float</h4>
1.
{% highlight ruby %}
overflow: auto;
{% endhighlight %}

2.
{% highlight ruby %}
.selector {
  display: table;
  clear: both;
}
{% endhighlight %}

<h4>list-style-type</h4>
[list-style-type][list-style-type]















[list-style-type]:https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type
