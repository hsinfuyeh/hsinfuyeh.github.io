---
layout: post
title:  "CSS Syntax Notes"
date:   2016-03-31 20:17:00 +0800
categories: jekyll update
---
<h3>Back to Top</h3>
{% highlight ruby %}
<h1 id="top">Title</h1>
<a href="#top"><p>Back to Top</p></a>
{% endhighlight %}

<h3>padding</h3>
{% highlight ruby %}
padding: up right bottom left;
padding: up right and left bottom;
padding: up and bottom right and bottom;
{% endhighlight %}

<h3>background</h3>
{% highlight ruby %}
background: color url(#) repeat center(background-position) / cover(background-  size)
{% endhighlight %}

<h3>fix the collapse after float</h3>
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

<h3>text-shadow</h3>
{% highlight ruby %}
text-shadow: inset horizontal vertical blur-radius spread color;
{% endhighlight %}
inset: shadow is inside the object.<br>

<h3>Add fonts</h3>
Font Squirrel: [https://www.fontsquirrel.com/][Font Squirrel]
{% highlight ruby %}
@font-face {
  font-family: 'name of font';
  src: url('#');
}
{% endhighlight %}



















[Font Squirrel]:https://www.fontsquirrel.com/
