---
layout: post
title:  "CSS Syntax Notes"
date:   2016-04-01 18:39:30 +0800
categories: jekyll update
---
<h3>References</h3>
MDN CSS media queries: [https://teamtreehouse.com/library/css-basics/designing-with-the-latest-features/media-queries][MDN CSS media queries]
<br>
MDN @media:
[https://developer.mozilla.org/en-US/docs/Web/CSS/@media][MDN @media]
<br>
<br>
{% highlight ruby %}
@media (max-width: 960px) {
    body {
      background: royalblue;
    }
}
@media (max-width: 480px) {
  body {
    background: darkred;
  }
}
@media (min-width: 481px) and (max-width: 700px) {
  body {
    background: seagreen;
  }
}
{% endhighlight %}
<br>
{% highlight ruby %}
<mata name="viewport" content="width=device-width">
{% endhighlight %}
