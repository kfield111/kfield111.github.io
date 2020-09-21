---
layout: post
title:      "The Key To Looping…To Looping…To Looping"
date:       2020-09-21 00:46:34 +0000
permalink:  the_key_to_looping_to_looping_to_looping
---


As you become more familiar with code of any language, you should begin to notice patterns and repetitive code. In Ruby, many times this code comes in the form of if, elsif and else statements.

These statements are powerful and help us to perform some necessary logic when checking conditionals and then executing code depending on the result. However these if family statements can get out of hand pretty quick if we have multiple conditions to check. Thankfully there are processes in place to be able to iterate, or loop through our information and perform actions along the way.

The key portions of a loop iteration are 

*1. Statement

*The statement lets the code block know we are looking to loop through some stuff or continue to run until a condition is met and it also tells the code how we are going to check on the conditional that is passed through. This will become more apparent in a second.*

*2. Conditional

*The conditional sets up the "conditions" that must be met in order to instruct the loop what to do and when to stop. Until the conditional is satisfied, the loop continues to run. NOTE: Be careful that your conditional is never satisfied or else you will end up in an infinite loop*.

*3. Do or Execution*

*This is what the code does during each iteration through some data or what the code executes each time the loop runs.*

Loops are extremely useful for performing actions on items within an array or hash as you can let the loop do all the hard work for you. Loop iterations are also handy for incrementing values since a specific block of code is running over and over again until its told to stop. 

An example of this is setting a "count" method with a variable of "number =0" to run UNTIL the number equals 10. If you set your variable to be updated by 1 (number += 1) inside your loop then each time the loop runs it will update the number variable to be one number higher than it was before. When it reaches 10, the CONDITIONAL is then met and the loop stops.

There are many ways to iterate (loop) through data. I suggest you take some time to play around with simple loops of different types and see what each one gives you. Each type of loop is a tool that can be used in a multitude of ways, but they all share the same general functionality we spoke about here.
