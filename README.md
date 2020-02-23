# Project: Custom Calculator

### tl;dr
You will create a python program that does a complex calculation based on information provided by the user. Then you'll record a short narrated video of your code and program. [Click here to see an example.]()

### The details...
Your calculator will not be like any ole calculator. Your calculator will use a unique custom formula that you come up with to tell the user something interesting that they would not have otherwise thought of.

For example: your experience of the temperature outside is not *really* what the weather app says it is. Imagine two scenarios:
1. the weather app says it's 30 degrees outside. It's also windy and cloudy and damp. You step outside and think "wow, it feels more like -10!"
2. the weather app says it's 30 degrees outside. But it's calm and sunny and dry. You step outside and think "hey, feels like 50!"
So you could make a "feels like" calculator, like this:
```
+------------------------------------+
|                                    |
|     FEELS LIKE CALCULATOR v 1.4    |
|                                    |
+------------------------------------+

Welcome! I'm here to help students in Mr. Cirrus' Meteorology class
get a better understanding of how warm or cold it'll feel outside today.
First I need to ask you a few questions:

 1. What's the reported temperature? ___  (user gives input)
 2. What's the wind speed? ___  (user gives input)
 3. What's the percent cloud cover? ___  (user gives input)

* OK! Even though your app says it's ___ degrees, it'll feel more like ___.

~/unit_5/ $ _   (program exited)
```

Your app also needs to do some error checking in case the user enters some unreasonable values, like this:
```
+------------------------------------+
|                                    |
|     FEELS LIKE CALCULATOR v 1.4    |
|                                    |
+------------------------------------+

Welcome! I'm here to help students in Mr. Cirrus' Meteorology class
get a better understanding of how warm or cold it'll feel outside today.
First I need to ask you a few questions:

 1. What's the reported temperature? ___  (user enters 5000)
 
 ** ACK! 5000? That can't be right. Please try again. **
 
~/unit_5/ $ _    (program exited)
```

### Checklist for a score of Proficient
* You have a working program.
* Your program starts by printing a title in a box and a description of what it does and which class it is for.
* Your input prompts and outputs are formatted cleanly.
* Your formula takes into account at least three inputs from the user.
* You have at least one if statement for each user input that exits the program if the user provides an unreasonable value.
* Your calculator is relevant to a topic you are studying in another class, and is interesting to your fellow students in that class.


### Checklist for Distinguished Option
* You showed your program to a fellow student enrolled in the class your calculator relates to, and not enrolled in computer programming.
* You solicit at least one piece of usable feedback from that classmate and incorporate that feedback into your program.
* In a comment at the top of your program you thank that classmate by name and describe the update that is a result of their feedback, like this:
```
 1   # Feels Like Calculator
 2   # by Andy Smith, March 4, 2020
 3   # v1.4 includes updated formula to give sunshine more weight
 4   # thanks to Liz Warren for this feedback
```

### Walkthrough
1. Fill out the "Designing Your Formula" worksheet.
1. Copy/paste your code from your lunch_order.py program into a new file called calc.py. Then save and run calc.py to be sure it works.
2. Start changing calc.py to fit the needs of your new program.
3. Your new program should start by printing a box with a title. You can go basic like in the example above, or use other symbols to make it a bit fancier.
4. Update variable names or create new variables with good names.
5. Be sure you're using int() and float() as needed.
6. Test your code often!
7. If you're going for the distinguished option (and yes, you should!), show your program to a fellow student from the class your calculation relates to (that fellow student must be enrolled in that class and not enrolled in any Computer Programming class with Mr. Smith this year -- we're going for feedback from a real user who is not a programmer).


### How to Submit
Go to this assignment in google classroom and open the Mastery Check attachment. Follow the instructions in there, and then press 'turn in'.

