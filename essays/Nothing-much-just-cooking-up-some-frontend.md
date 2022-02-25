---
layout: essay
type: essay
published: true
title: Nothing much, just cooking up some frontend
# All dates must be YYYY-MM-DD format!
date: 2022-02-24
labels:
  - ICS 314
  - Semantic UI
---
## Favorite Food
If you ask me what my favorite food is, I would say (after long deliberation because I love eating a lot of things): dumplings, especially the ones that my mom makes. The savory filling enveloped in chewy dough, paired with vinegar can make anyone hungry (aka elicit an unconditional response—yes I just had a psychology test). 

Relatively recently, my mom started making dumplings entirely from scratch. She used to buy the dumpling wrappers pre-made, but they’re quite expensive and are usually out of stock. However, creating dumplings from scratch is no small feat. The filling requires an array of ingredients (e.g. egg, pork, starch, a veggie like chives, condiments); the dough needs to be mixed (stickiest thing ever), put to bed and “sleep” for a few hours, kneaded, divided into spheres that are about an inch in diameter and then rolled out into dumpling wraps. Then each dumpling wrap needs to be filled and folded to make a single dumpling. Quite a bit of work, huh? I’ve been trying to learn how to make dumplings from my mom and let’s just say my dumplings look less than stellar and often break once put into boiling water.

## Can I get a landing page deluxe with a side of a footer?
How does this relate to software engineering? Well, building a web page is like cooking a dish. And what you use to help you build the page can affect the end result. In the past, I’ve mainly just used raw css and html to build pages. While it was fun to do, it was also incredibly difficult to build anything that was moderately presentable. Essentially, I’m a novice cook cooking from scratch. Thankfully, this is where UI frameworks come in. 

Many UI frameworks (like Semantic UI) can help speed up the development process because they provide pre-made components and have built-in styling. One such pre-made thing is a menu component that automatically styles things that are supposed to be a part of the menu as long as you give these things a class of “item” (allowing it to use “Semantic UI magic” to hook everything up). Or the container component has preset margins that are already aesthetically pleasing. Semantic UI is special because using it is like speaking/writing in plain English. For example, to use a container that has centered grids, you just add the class name “ui centered grid container” to a div and voila, your dumpling is ready to be served. 

Semantic UI not only speeds up the development process, but can also make the entire website look more consistent. However, the consequences of using a UI framework is that it can be quite a burden when you want to override defaults and do more customization. When you’re a master chef, you need to be able to fine tune all the ingredients—those chives (margins) need to be 5mm (5px) thick. Therefore, one needs to weigh the cost and benefits of using a UI framework. 

## Crab and Imitation Crab
One of the tasks we had to do for class was find a webpage to rebuild using Semantic UI. At first I was dreading this assignment because I could only recall how long it took to make anything pretty using html and css. In fact, I’m very particular about how things look on a webpage, so I can spend hours making everything line up exactly how I want it to. However, creating this webpage surprisingly took less time than I thought. Here are the results (left column has the originals while the right column has my semantic-ui attempt):

<div style="height: 375px">
<img class="ui left floated rounded image" width="47%" src="../images/ICS314_SemanticUI_original1.png">
<img class="ui right floated rounded image" width="47%" src="../images/ICS314_SemanticUI_knockoff1.png">
<img class="ui left floated rounded image" width="47%" src="../images/ICS314_SemanticUI_original2.png">
<img class="ui right floated rounded image" width="47%" src="../images/ICS314_SemanticUI_knockoff2.png">
</div>

At the end of the day, I still think it’s important to practice raw html and css because UI frameworks hide a lot of intricate details about html and css. Additionally, UI frameworks won’t be able to meet every look you want and you’ll eventually run into a situation that requires more customization. In other words, if I want to create a never-seen-before dumpling, I can’t just buy it from the store—I will have to make it (or at least parts of it) from scratch. 
