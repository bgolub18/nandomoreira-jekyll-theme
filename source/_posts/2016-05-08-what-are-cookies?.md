---
layout: post
title: "What are Cookies?"
date: 2016-05-08 08:45:10
comments: true
description: "What are cookies and sessions and why should I know about them?"
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

I’m sure you know what a cookie is, as in a chocolate chip or snickerdoodle cookie, but this is about the <em>other</em> type of cookie. You might have noticed how after doing some online shopping, you might go to another website and see an advertisement for the item you were just looking at. Before explaining how that works, it’s important to understand exactly what a cookie is. A cookie is really an addition to HTTP and HTTPS. It’s not a method, like GET or POST, but it is usually sent along with requests <a target='_blank' href="http://shiflett.org/articles/the-truth-about-sessions">1</a>. The cookie is typically a header written in plain text with these methods and gives basic info on the client or web page and is then stored in the browser. Servers access these cookies to see browsing trends and also sometimes for security purposes. Businesses now are using cookies to generate a profile for you while you surf their website <a target='_blank' href="http://www.allaboutcookies.org/cookies/">2</a>. They then use this profile to target certain advertisements that you are more likely to click on in the hopes that you spend some money on them. The security thing is where it gets tricky. Because cookies are attached to the HTTP requests and written in plain text, it is incredibly easy for hackers to read your passwords and info if they are on the same wifi network <a target='_blank' href="http://lifehacker.com/5853483/a-guide-to-sniffing-out-passwords-and-cookies-and-how-to-protect-yourself-against-it">3</a>. Once coders and hackers recognized how insecure that is, they created sessions. Sessions establish a unique ID and the server recognizes this ID and uses it to securely find the right data and not have it written in the code <a target='_blank' href="http://stackoverflow.com/questions/3804209/what-are-sessions-how-do-they-work">4</a>. Of course, it is still significantly more secure to use HTTPS websites, which will encrypt everything, making it much harder to find your information, even without using sessions, but most HTTPS website use sessions anyways. The moral of the story is that even though cookies have a very innocent name, they are infact quite dangerous and in many cases a security risk, so use the internet with caution.



Sources:
1. <a target='_blank' href="http://shiflett.org/articles/the-truth-about-sessions">http://shiflett.org/articles/the-truth-about-sessions</a>
2. <a target='_blank' href="http://www.allaboutcookies.org/cookies/">http://www.allaboutcookies.org/cookies/ </a>
3. <a target='_blank' href="http://lifehacker.com/5853483/a-guide-to-sniffing-out-passwords-and-cookies-and-how-to-protect-yourself-against-it">http://lifehacker.com/5853483/a-guide-to-sniffing-out-passwords-and-cookies-and-how-to-protect-yourself-against-it</a>
4. <a target='_blank' href="http://stackoverflow.com/questions/3804209/what-are-sessions-how-do-they-work">http://stackoverflow.com/questions/3804209/what-are-sessions-how-do-they-work</a>