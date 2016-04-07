---
layout: post
title:  "JaveScript syntax note"
date:   2016-04-07 19:22:42 +0800
categories: jekyll update
---
<h3>var name rule</h3>
{% highlight ruby %}
letters numbers $ _
{% endhighlight %}
Can't start with a number.

<h3>Untitled</h3>
{% highlight ruby %}
var visitor = prompt('What is your name?');
var message = 'Hello ' + visitor + ". Welcome to my blog.";
message += "I am so glad that you came here to visit, "
message += visitor;
message += ". Please come again, when you are free.";
document.write(message);
{% endhighlight %}

{% highlight ruby %}
message += "I am so glad that you came here to visit, "
{% endhighlight %}
equals to
{% highlight ruby %}
message = message + "I am so glad that you came here to visit, "
{% endhighlight %}
