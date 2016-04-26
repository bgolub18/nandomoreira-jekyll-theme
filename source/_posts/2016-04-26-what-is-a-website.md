---
layout: post
title: "What is a Website?"
date: 2016-04-26 08:45:10
comments: true
description: "What exactly is a website?"
keywords: ""
categories:
- Combos
- Coding
- Basics
- Web Applications
tags:
- We made it
- Apple, the only way
- GROWTH
- Code like a pro
---

Whether it’s Facebook, Google, Amazon, or Youtube, everyone has a favorite website, but most people couldn’t accurately define a website. So what exactly is a website? A website is really just a collection of files that is being shared by the host <a target='_blank' href="https://nycda.com/blog/how-the-internet-works/">1</a>. Of course, there are typically many files which all serve different purposes, like the front end and back end. But when you visit a website like Youtube, you, the client, are requesting that the server, or host, sends you the files <a target='_blank' href="https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/How_the_Web_works">2</a>. The client and host are able to communicate because most websites have similar protocols. Most websites uses HTTP which stands for Hypertext Transfer Protocol. A growing number of websites are using HTTPS which is the more secure version of HTTP. These protocols establish many methods both clients and hosts can use to send and receive information and files. But, in order to understand these protocols, it’s important to understand exactly what clients and hosts are. The client is the computer trying to access the website. The host, usually a server, is the computer holding the files that the client is trying to see. Companies use servers to keep the files available 24/7. If it was just a personal computer, it likely couldn’t handle the traffic associated with popular websites and if the computer was turned off, the files would no longer be accessible. The information is also typically very large, so computers use HTTP and HTTPS to transfer small packets of information <a target='_blank' href="http://www.bbc.co.uk/guides/z3tbgk7">3</a>. These packets are sent in binary through routers and assembled as instructed according to HTTP and HTTPS. Most computers also don’t fully recognize facebook.com. Computers use Domain Name System (DNS) to associate the name of the website with the IP address. Computers need to read the IP address so the routers know where to send the packets, but humans prefer to read actual names instead of IPs, so DNS was created to accommodate both computers’ and humans’ needs. Now, the next time you visit facebook.com, you’ll understand exactly what is going on behind the scenes that allows you to see all of your friends’ posts.


Sources:
1. <a target='_blank' href="https://nycda.com/blog/how-the-internet-works/">nycda.com</a>
2. <a target='_blank' href="https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/How_the_Web_works">developer.mozilla.org</a>
3. <a target='_blank' href="http://www.bbc.co.uk/guides/z3tbgk7">www.bbc.co.uk</a>