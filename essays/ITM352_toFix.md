---
layout: essay
type: essay
published: false
title: toFix or not toFix
# All dates must be YYYY-MM-DD format!
date: 2021-09-26
labels:
  - ITM 352
  - HTML
  - javascript
---

For this WOD, we used HTML and javascript to create a simple, tabulated sales receipt that included the product name, price, quantity, extended price, subtotal, tax, and grand total. For each product, the name, price, quantity, and extended price were stored as variables in javascript. The subtotal, tax, and grand total were calculated variables based on the extended prices. Further details about the WOD can be found [here](https://dport96.github.io/ITM352/morea/060.expressions-operators/experience-invoice1.html). 

I feel like this WOD really helped me solidify my understanding of how javascript can work with HTML. Creating all of the variables and using the variables within the `document.write` function was straightforward for the most part. One part that slowed me down was figuring out what data type certain variables were after manipulating them. Specifically, I realized that my use of `.toFixed` was changing some of the variables into Strings which caused trouble when I tried doing other manipulations. In the end, I found that using the `.toFixed` only at the last second (in the HTML of `document.write`) was the most straightforward. 

What I did similarly for this WOD was I did this WOD completely on my own first (without watching the video) and then watching the video to see if I could have done something in a better fashion. One thing I did change between my first attempt and second attempt was to utilize a script tag for each `document.write` use. What I did differently for this WOD was I first looked at all of the steps in advance and referenced the labs we did in class to help me figure out how to complete each step. 

To be better prepared for my next WOD, I think I should more thoroughly review some of the lectures and labs on code that I don’t have too much experience with. For the next WOD, I will try to do this and maybe I will also try to review the instructions for the WOD before a class section so that I can ask for clarifications. 
