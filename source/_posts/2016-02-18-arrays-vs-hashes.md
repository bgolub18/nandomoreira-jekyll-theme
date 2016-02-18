---
layout: post
title: "Arrays vs. Hashes"
date: 2016-02-04 08:53:10
comments: true
description: "A comparison of data structures in Ruby"
keywords: ""
categories:
- Combos
- Coding
- Basics
tags:
- We made it
- Apple, the only way
- GROWTH
-Code like a pro
---

For those who are learning to code using Ruby, they are fortunate to have a couple of tools for storing data: arrays and hashes. Arrays and hashes appear relatively similar in their coding, but their uses can be very different. As one user concisely put it, an array is like a list and a hash is like a collection of pairs of information.<a href="https://www.codecademy.com/forum_questions/52a69117282ae3085d000d63">1</a> With an array, each item within the data structure is listed and is assigned a number. So if I made an array called homework, the array might look like homework = [‘math problems’, ‘formative questions’, ‘english reading’, ‘history quiz’]. Then if I wrote puts homework[0], the computer would display math problems.<a href="https://pine.fm/LearnToProgram/chap_07.html">2</a> Another useful real life example for an array could be the members of a class or a grocery list. Hashes store what’s known as a key and a value for each key.<a href="http://ruby-doc.org/core-2.2.0/Hash.html">3</a> Hashes are special because they basically have their own syntax in the form of a symbol. Symbols can replace strings as keys in a hash. If I made a hash for prices and items on a menu, it might look something like menu = {:salad => “$5”, :sandwich => “$7”, :soup => “$4, :coffee => “$2”}. If I then wanted to know the price of a coffee, I could write puts menu[:coffee], and the computer would display $2. 
Although arrays and hashes have similar methods (no pun intended) of storing data, they are often used for very different things, but the best uses are ones that can utilize both. For example, you could easily make a grocery list using an array, but what if you wanted to organize all of your items by type? You could create a hash with keys like “dairy” or “fruit” and for the values you could make arrays that list the many dairy items or fruits you need to buy. 
Thus, the next time you decide to code and find the need for a data structure, consider more than just an array or a hash. The best way to utilize the advantages of each data structure is to use the structures together.

Sources
1. <a href="https://www.codecademy.com/forum_questions/52a69117282ae3085d000d63">codeacademy.com</a>
2. <a href="https://pine.fm/LearnToProgram/chap_07.html">Learn to Program by Chris Pine</a>
3. <a href="http://ruby-doc.org/core-2.2.0/Hash.html">Ruby Docs</a>
