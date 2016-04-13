---
layout: post
title:  "JavaScript Syntax Notes"
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

<h3>String</h3>
{% highlight ruby %}
var stringToShout = prompt('What should I shout?');
var shout = stringToShout.toUpperCase();
shout += '!!!';
alert(shout);
{% endhighlight %}
[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String][String]

<h3>numbers</h3>
`parseInt: converts string into number`

<h3>Math</h3>
`Math.floor: round the number down`<br>
`Math.ceil: round the number up`<br>
`Math.random: give a randon number from 0 to 1 (not include 1).`<br>

{% highlight ruby %}
var dieRoll = Math.floor( Math.random() * 6 ) + 1;
alert('You rolled a ' + dieRoll);
{% endhighlight %}
You will get a random number from 1 to 6.

<h3>conditional statement</h3>
`> Greater than`<br>
`>= Greater than or Equal To`<br>
`< Less than`<br>
`<= Less than or Equal to`<br>
`== Equal to`<br>
`=== Strict equal to`<br>
`!= Not equal to`<br>
`!== Strict not equal to`<br>
{% highlight ruby %}
if {
} else {
}
{% endhighlight %}
<br>
{% highlight ruby %}
if {
} else if {
} if {
}
{% endhighlight %}<br>

<h4>and(&&)</h4>
{% highlight ruby %}
if (20 < age && age > 30) {
}
{% endhighlight %}
Have to satisfy both of two conditions.<br>

<h4>or(||)</h4>
{% highlight ruby %}
if (agree === 'yes' || agree === 'y') {
}
{% endhighlight %}
Only have to satisfy one of conditions.

<h3>comment</h3>
`// single line comment`<br>
`/* blablabla */ multiple line comment`








[String]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String
