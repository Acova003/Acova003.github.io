---
layout: post
title:      "Pry Is a Girl's Best Friend"
date:       2018-09-01 06:09:07 +0000
permalink:  pry_is_a_girls_best_friend
---


Diamonds are to Marilyn Monroe as pry is to this very nerdy programer.  There is a Ruby gem called 'pry' that can save you hours of figuring out why you're getting that nil class error. Pry is in fact, my best friend. 

What is pry? 

When we use irb, we are given a new environment that we have to write or paste code into. The pry gem takes the code that you've already written and turns that into an interactive enrvironment. Don't know what array is being passed into your method? Pry lets you 

Let's see this in action...


Here we have a method that adds two to a number that is passed in

![Without pry](https://photos.app.goo.gl/fWrAfXnkZRRhUz6B9)

What is the value of sum? Let's look under the hood with pry... 


You can use pry by requiring pry at the top of the file and add binding.pry inside of the method. 

![Adding pry](https://photos.app.goo.gl/jE5grHubsgVaiA7j8)

Run the code as you normally would. Now you will see a cool REPL that you can play with. Want to know what sum returns? Just ask! 

![Pry output](https://photos.app.goo.gl/eJWGYxwEXBouapAn8)

Pretty neat huh? By using pry, we can peak under the hood of individual elements of our code. We can then interact with the code that we've written to test and debug using pry. 


