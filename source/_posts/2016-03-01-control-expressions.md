---
layout: post
title: "Control Expressions"
date: 2016-03-01 09:24:10
comments: true
description: "A comparison of between if and case statements"
keywords: ""
categories:
- Combos
- Coding
- Basics
- Conditionals
tags:
- We made it
- GROWTH
- Code like a pro
---

If you are reading this, then you want to learn about if statements in ruby. When you are reading this, you will also learn about case statements. These two sentences were examples of both an if statement and a case statement, respectively.<a target='_blank' href="http://ruby-doc.org/core-2.2.0/doc/syntax/control_expressions_rdoc.html">1</a> If statements and case statements both fit under the same category known as control expressions, but are more commonly known as conditionals. They are also very similar in structure and function. If a / represents the end of a line, an if statement would look like this: If (condition) / (return value) / else / (other return value) / end. A case statement would appear as: case x / when (condition) / (return value) / end. They accomplish pretty much exactly the same thing, so how do you know which to use? If statements work really well if you have only a few conditions. But if you have a lot of conditions, writing out a case statement will require fewer characters, and will thus work more efficiently and take up less space.<a target='_blank' href="http://www.daniellesucher.com/2013/07/ruby-case-versus-if/">2</a> What also makes case statements unique from if else statements is case statements or the only methods that use the === operator.<a target='_blank' href="http://www.skorks.com/2009/08/how-a-ruby-case-statement-works-and-what-you-can-do-with-it/">3</a> This operator is unique because unlike the double equals sign operator, this means more than just a = b. The triple equals operator is also practically never seen in code because it lies in the syntax of ruby case statements, meaning it is implied when someone writes “when”. So, this triple equals operator, when used in the context of when a / b, basically asks the computer does “b” belong in the same set as “a”?<a target='_blank' href="http://stackoverflow.com/questions/4467538/what-does-the-operator-do-in-ruby">4</a> In the end, the choice to use and if statement or a case statement is a mostly arbitrary one. Choosing one over the other can only really save you microseconds of processing or a few bytes of storage. The only real reason to choose one over the other is that it might make reading a program slightly easier. 

Sources:
1. <a target='_blank' href="http://ruby-doc.org/core-2.2.0/doc/syntax/control_expressions_rdoc.html">codeacademy.com</a>
2. <a target='_blank' href="http://www.daniellesucher.com/2013/07/ruby-case-versus-if/">codeacademy.com</a>
3. <a target='_blank' href="http://www.skorks.com/2009/08/how-a-ruby-case-statement-works-and-what-you-can-do-with-it/">codeacademy.com</a>
4. <a target='_blank' href="http://stackoverflow.com/questions/4467538/what-does-the-operator-do-in-ruby">codeacademy.com</a>
