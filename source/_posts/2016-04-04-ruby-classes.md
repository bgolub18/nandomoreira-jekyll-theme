---
layout: post
title: "Ruby Classes"
date: 2016-04-04 09:22:42
comments: true
description: "The importance of classes in object oriented design"
keywords: ""
categories:
- Combos
- Coding
- Basics
- Classes
tags:
- We made it
- GROWTH
- Code like a pro
---

When you sign up for facebook, snapchat, or instagram, you are always asked to create a profile which follows some form of universal template. These profiles are great examples of what a class is in Ruby and other programming languages. A class in ruby allows the programmer to create attributes and behaviors for each object within the class <a target='_blank' href="http://ruby-doc.org/core-2.2.0/Class.html">1</a>. The word “attributes” is intentional there. Classes have whats known as instance variables, which are also known as attributes, because the variables apply to the whole class, but they can be different for each object of the class <a target='_blank' href="http://phrogz.net/programmingruby/tut_classes.html">2</a>. Going back to the social network example, if the class was Profile, things like the username, password, birthday, email, etc. are examples of attributes of the class and would likely be instance variables in the code. Sometimes people need to change attributes or they need to read what the attributes are, so there are the attr_accessor, attr_writer, and attr_reader methods. These methods allow users to read what the attributes say (attr_reader) or change the attributes (attr_writer). The accessor method creates both the reader and writer method for the attribute the user chooses <a target='_blank' href="http://stackoverflow.com/questions/5046831/why-use-rubys-attr-accessor-attr-reader-and-attr-writer">3</a>. Classes also often use the initialize method at the beginning of their code. The initialize method establishes a protocol of what attributes should be set right when an object of that class is created. The initialize usually uses parameters, which are the things in the parentheses next to intialize (see photo below). These parameters usually set the values for the attributes, basically making sure the object of the class has the basic qualities it needs to function properly. 
Classes in Ruby allow users to avoid redundancy and write out the code for many objects once. The code in the class is often considered a template for the objects. Object oriented design revolves around the use of classes to save redundancy and space and also create uniform objects that can interact with one another. 


	class School
		def initialize (name, grade, classes, size)
			@name = name
			@grade = grade
			@classes = classes
			@size = size
		end
		attr_accessor :name, :grade, :classes, :size
		def set_hours
			puts "How long should your school day be?"
			@school_day = gets.chomp
		end
		def set_clubs
			puts "What clubs does your school have?"
			@clubs = []
			@clubs << gets.chomp
		end
		def add_club
			puts "What club do you want to add?"
			@clubs << gets.chomp
		end
	end		

Sources:
1. <a target='_blank' href="http://ruby-doc.org/core-2.2.0/Class.html">ruby-doc.org</a>
2. <a target='_blank' href="http://phrogz.net/programmingruby/tut_classes.html">phrogz.net</a>
3. <a target='_blank' href="http://stackoverflow.com/questions/5046831/why-use-rubys-attr-accessor-attr-reader-and-attr-writer">stackoverflow.com</a>

