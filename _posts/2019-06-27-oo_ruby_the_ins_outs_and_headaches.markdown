---
layout: post
title:      "OO RUBY: The ins, outs and headaches"
date:       2019-06-27 14:08:16 +0000
permalink:  oo_ruby_the_ins_outs_and_headaches
---


OO RUBY is the cornerstone of modern age application development. The following quote bes summarized the essence of Objec Oriented Programming: 

"An object-oriented approach to application development makes programs more intuitive to design, faster to develop, more amenable to modification, and easier to understand."
—Object-Oriented Programming with Objective-C, Apple Inc.

In the modern era of Application Development (appDev) efficiency and speed are king. The issue is being able to make applications that can be easily interpreted, are effective and welcome new functionality to grow. Que the ever popular "object". 

By using an object we can bundle a physical representation for us in "human language" and transcribe it into binary code "computer language". For example, when we want to describe an product such as "Rope" there has to be a way to describe it to the application, and also save multiple instances of ropes with each having individual descriptions. 

We can represent a Rope as having a #:length, #:diameter, and  #:maxLoad. Instead of us nesting an array into another array with allot of code to set up their relations, we can group all these pieces that describe a rope into a RopeObject, which will keep all of the specifics of this rope in one place. Later on we can have an Array of RopeObjects which have the different description of each rope we want the application to know about.
