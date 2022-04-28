---
layout: post
title: "Intro to offensive security"
date: 2022-04-27
categories: jekyll update
---

{% highlight ruby %}
Web app enumeration - what is website enumeration
{% endhighlight %}

Website enumeration is one of the ways that a web app can be hacked. How is it performed? Very easy. There's this tool called Go Buster that takes a wordlist and runs a check against to look for valid directories in the web app most likely its an admin portal through which admin tasks can be performed.

OK, great! now that we know what website enumeration is and what tool is used to perform it. Our next question should be how to use Go Buster. Again its a super simple tool to use. We just need two things which are website url and a wordlist. Its syntax is as written below

{% highlight ruby %}
gobuster -u "http://websiteurl.com" -w wordlist.txt
{% endhighlight %}
