---
layout: post
title:  "Robot Ball | inspired from Sphero"
date:   2016-03-15
excerpt: "Robot Ball | inspired from Sphero"
project: true
comments: false
---
<iframe width="560" height="315" src="//www.youtube.com/watch?v=VSxVMzAeqBA&feature=youtu.be" frameborder="0"> </iframe>

Video embeds are responsive and scale with the width of the main content block with the help of FitVids.

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

{% highlight html %}
<iframe width="560" height="315" src="//www.youtube.com/watch?v=VSxVMzAeqBA&feature=youtu.be" frameborder="0"> </iframe>
{% endhighlight %}

## Description
CSE 360: Computer Interfacing Final Project

Controlling DC motors using Arduino Uno via Bluetooth.
>Required Components: Arduino Uno, Bluetooth Module, DC motor. L-293D Bridge, Battery

This is the demonstration of the project. We took help from the following links to connect you components:

Arduino+Bluetooth+Android: www.youtube.com/watch?v=x3KAXjnP06o
How to use the L293D Dual H-Bridge: www.youtube.com/watch?v=5nDaHJqruq0
