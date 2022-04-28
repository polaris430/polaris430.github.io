---
layout: post
title: "Intro to offensive security"
date: 2022-04-27
categories: jekyll update
---

> What is Website Enumeration?

Website Enumeration is one of the ways by which a web app can be hacked.

> How is it performed?

Very easy. There's this tool called Go Buster that takes a wordlist and runs a check against it looking for valid directories in the web app most likely an admin portal through which admin tasks can be performed.

> How to use it?

Syntax: gobuster -u "http://websiteurl.com" -w wordlist.txt
