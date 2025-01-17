---
layout: essay
type: essay
published: false
title: That was so fun!
# All dates must be YYYY-MM-DD format!
date: 2021-12-16
labels:
  - ITM 352
  - Sessions/Cookies
  - HTML
  - css
  - Javascript
  - Servers
---

### Briefly describe your system (e.g. A store selling Pokemon game cards)
In this assignment, I created a pretend e-commerce website that sells plants (mainly flowers).

### Any notable shortcomings, bugs, problems, or additional features not implemented?
I think the most notable shortcomings is that there are some functions that should’ve been consolidated into one function in order to avoid redundant code. There are no bugs that I know of, but I did realize while I was developing that the quantity of a product a user can put into their count doesn’t consider someone else already having a quantity of that product in their cart. Although this wasn’t a requirement for this assignment, in the future, I should implement a count of a certain product already in someone else’s cart in order to avoid this clash. Some additional, extra credit features that I didn’t have time to implement was the saving of a logged-in user’s cart between server runs.

### Describe what you are most proud of about your system:
I am really proud of the interface because it is simple and straightforward. I’m really glad I had time at the end to fiddle with styling the application and adding little decorations to boost the overall look of my website. I am also really proud of the alert system (notifying the user of session expiration) because I was able to make the alert appear no matter what page the user is on. Although I looked online on how to do this, none of them really considered an MVC architecture, so this took me a bit to figure out. 

### Describe what you are least happy with your system:
I think I need to work on making more modular code because when I worked on Assignment 2 and 3, I sometimes had trouble modifying things (e.g. forms) to meet the new requirements because of old design decisions I made. I also feel like there’s a lot of lines of code in just the server.js and it would’ve been nice to separate them into separate files if possible in order to make it easier to work with. I’m not entirely sure how to do this because most of the html needs to be generated on the server side (because of the MVC architecture), but this is something I’ll try to do next time. 

### How was developing this assignment different than assignment #2?
I actually found assignment 3 easier in some ways because after working on assignment 2, I had a much more solid understanding of POST and GET requests and I became more aware of designing with the idea that multiple users would be using the system at once. By using sessions, I was able to isolate a user’s experience which helped me with developing this assignment. 

### When you ran into a problem, what did you do to address it?
When I ran into a problem, I first thought about the entire procedure that led up to that line of code and then started debugging from where I thought the root problem was. Often I would also search up the error message on Stack Overflow in order to understand what was going on. I also asked Professor Kazman for guidance when I got really stuck. 

### Describe what worked well in doing this assignment?
What worked well for me was reading through the instructions in full multiple times before starting so that I connected them all in my mind first. Doing this allowed me to see which parts would affect each other and influenced how I designed certain parts. Another thing that worked well for me was coding a few lines at time and trying to fully understand what was going on helped me stay on track. 

### Describe what did not work well in doing this assignment?
Once the application got bigger, I found that I couldn't do as thorough testing as I would’ve liked. This led me to causing some bugs in other parts of my code that I didn’t even notice. So I really want to learn how to do automated testing. What also didn’t work well was I had trouble sectioning parts of a webpage when styling so next time I think it might be helpful to use a css framework like Bootstrap. 

### What did you learn from doing this assignment?
I learned how to use sessions; how important modularization is (I did modularize UI components which I found very helpful); how to send an email from the server; and in general how to design an entire application using the MVC architecture.

### If you could go back in time and do things differently, what would you change?
If I could go back in time, I would've created an external stylesheet from the get-go, because after creating internal stylesheets, combining them all was quite difficult. I would also redo the file I/O part because there are some parts of it that can be simplified and cleaned up. Lastly, I would make it where I can turn off logging in because I found it very tedious to keep logging in when testing a feature or maybe if I could go back in time, I should’ve used nodemon but I’d definitely be worried about nodemon not actually updating. 

### Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging
 - Thinking about how to do something - 40%
 - Writing code (but do not include testing - 35%
 - Testing and debugging - 25%

### Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself) and explain briefly your rationale for the percentage breakdown. Be sure to include an overview of what specifically you and your partners contributed (e.g. “I worked on the security and my partner 1 worked on personalization”)
I worked on this assignment myself and got to have fun working on all the features!
