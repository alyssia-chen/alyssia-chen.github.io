---
layout: essay
type: essay
title: "I see a unicorn in the clouds"
date: 2022-05-28
labels:
- Software Engineering
- Design Patterns
---
## What am I looking at?
Sometimes when I’m super bored because I’m waiting for someone or something, I’ll look for objects in the vicinity to amuse me. Occasionally, it’s a plain old wall or ceiling, but if you look closer, the light and shadows that create the texture of the surface form a chaotic canvas that’s ripe to be painted with. Even though there’s nothing but random crevices, your brain automatically starts searching for patterns and makes you “see” things. I always find it fun to see what my brain comes up with. Of course, the brain’s capability to do this is not to help with boredom, but is really our brain's way to make sense of the world. In our day-to-day lives, our brain has to deal with a lot of stimuli and must process them fast enough to make good judgements. Using patterns allows us to make decisions faster and to notice stimulus that could be more important.

## A programmer's art
Visual patterns aren’t the only patterns that exist; we also have design patterns that exist in software engineering. In some ways it’s similar to the story I just mentioned in that every piece of code written by a programmer is a part of a wall and can be chaotic due to the uniqueness of each programmer’s style of coding and the problem they are dealing with. However patterns will start emerging through this chaos (actual patterns, not ones your brain comes up with from nothing) as certain styles of programming become more successful. In fact, design patterns are essentially strategies/methods involved in software development that are generic enough to suit multiple situations.

For example, one of the most famous classic patterns is called the Model-View-Controller (MVC) architecture. Essentially, an application is divided into 3 parts: its data (model), how things will look to the user (view), and the ins-and-outs of how things will interact (controller). By separating the 3, it allows the code to be better encapsulated and makes it easier for people to take upon tasks that they have more experience in without having to worry about parts they aren’t too clear about. In the current project I’m working on called [Warrior Ride Buddies](https://warrior-ride-buddies.github.io/), the MVC model is implemented. Specifically, the data are mongodb collections that have schemas that manage them; each of the .jsx pages include the views; and everything else (aka logic and react control) is the controller.

In another project I’m working on for my game design class, Unity (a game engine) utilizes the Observers design pattern. I think this pattern is really interesting because it allows certain procedures to occur when a certain event has occurred. So in a game, this could be “when a player has reached a certain number of points, turn on the enemy spawner and turn down the speed of the player.” Lastly, I remember in ICS 211 (Intro to CS II) we made a calculator class, but made it a Singleton (another design pattern). Looking back on it now (after learning about design patterns), I feel like I can better understand why this pattern was chosen and can also better question why we used it.

On the flipside, there are also anti-patterns which are design patterns that are “bad” in the sense that it doesn’t promote good software engineering practices. One that many know is “Spaghetti Code” which is when the code is so interweaved, it can be impossible to untangle it. Doing some research online on anti-patterns, I also found one called "Poltergeist" which is when there is essentially a phantom class that only calls functions of other classes and doesn’t really do anything itself. I had never heard of this term before, but after learning it, I feel enlightened because I’ve always wanted to know more about bad practices.

The “art” of coding has definitely been picking up in the past decades and with people using established design patterns, new ones are definitely bound to be created as future situations call for different guides.
