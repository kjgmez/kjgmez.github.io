---
layout: post
title:      "CLI Gem Scraper and coding for tomorrow"
date:       2018-11-28 16:16:59 +0000
permalink:  cli_gem_scraper_and_coding_for_tomorrow
---

Hi fellow developers, Kevin from the CodeVengers here to talk about the tokens of knowledge acquired while developing my first CLI GEM. The goal of the project is to create a CLI which uses OO programming to create relations between the different classes that make the code come to life. 

The requirements were as follows:

* Your CLI application must provide access to data from a web page.

* The data provided must go at least one level deep.

* Use good OO design patterns. You should be creating a collection of objects, not hashes, to store your data. 

After the many lessons, labs, videos and hours of playing with minor elements of a CLI, confidence levels and ideas flowed as to how to KISS (Keep It Simple and Short) the project and create a showcase for the acquired skills in these first two months of the engagement with Flatiron to become a Software Engineer. 

Thought process and logic for the program: 

1. We want to showcase the NY Red Bull Soccer team and the Players along with their stats.
* Website: [https://www.newyorkredbulls.com/players](http://)
* We need a Player Class to store all the players and their stats. The stats will include Player: Name, Position, Age, Height, Weight.
* We need a Scraper Class to extract the information from the above-mentioned website. Luckily the site itself has the information structured in Class format that is nested within the HTML code. 
* We can use Open-Uri to access the page code and Nokogiri to turn the code into a nested array. This means one can iterate over the different instances of Players to create the object attributes for Name, Position, Age, Height and Weight by using the same block of Scraping. 
* The Scraping Class needs to communicate with the Player Class to instantiate the objects.
* The CLI Class will be responsible for prompting the user for which player they want to know more about and calling the specific information from the Player Class. The logic must accept a number for the player from a printed list, ensure the inputs are valid and provide the information about the specified player.
* The program will exit once the user types "exit".  

The most intricate part of the program is the CLI that calls the information that has been gathered and sorted from scraping the page. The interactive user interface, which prompts the user for inputs, must only find the player the user selects and pull from the information stored in the object instances of the Player class. OO programming helps keep this process neat and repeatable with minimum code. This allows the developer to make understandable code that can be reused and updated.

The biggest challenge was to code today, thinking about what can be added tomorrow. Exchanging ideas with fellow programmers and being exposed to their code was crucial in finding efficient ways to make code "pretty", as I like to call it. "Pretty code" is easy to read, understand and simple enough to avoid repetitiveness or stink. Making it "pretty" will help the future engineer, or you, who is tasked with maintain and updating the app. This saves time and gives room to add functionality without affecting software/hardware balance. Changes in code can be minor by making code where variables only need to be changed in one place.   

OO programing has been a pivot point on how information is called, stored and processed. Being mindful of how much the program needs to sort, process and store information is critical in the day to day of a Software Engineer. Objects create a one stop access point to data that belongs to a specific item or class. By using objects to store all data in one location, processing time is reduced, efficiency is increased, and software/hardware use is efficient. This saves resources that can be better used or allocated to load balance other functionalities within the app.

In conclusion, we code for tomorrow with the tools we have today. A little more time in the present, along with collaboration with fellow developers, can help the future you work on an easily expandable app. Saving time and resources in these areas keep businesses at the cutting edge of technology.

