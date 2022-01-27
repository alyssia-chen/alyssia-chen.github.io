---
layout: essay
type: essay
published: true
title: Chen’s Quest for Smart Questions
# All dates must be YYYY-MM-DD format!
date: 2022-01-27
labels:
  - ICS 314
---
## “Hi Professor, I have 5 questions if that’s okay?”
Questions and I go way back. Okay not that back because I’m only 20 years old, but asking questions has really become second nature for me. When I was younger, I’d always be afraid to ask for help and clarification. Thankfully, the middle school (and later high school) I went to had a very small amount of students per grade level. In my class, we had a little less than 50. Because I got to know basically everyone in my class, I always felt like I was in a supportive, learning environment. Nowadays in college, while I can confidently ask questions (and believe me I do), the question now is: which questions to ask and how should they be refined to maximize what I learn from the response?

## Questions as a CS student
Specifically, as a computer science student, being able to find answers when you’re in the middle of coding is really a fine art (yes of creating the question but also not panicking when you can’t find the answer). 
For example, in my current internship at the Department of Taxation, I was tasked to convert a folder of xml schemas that are hierarchically organized into one schema. When I first started this task, it felt daunting because I had to learn what XML (and XML schemas) are and learn how to manipulate it in Visual Studio using C# (an IDE and programming language I’ve never used). During this time, a lot of research was done to get started on my task and also during this time, a lot of mistakes were made. Namely, I used search terms that weren’t the most accurate and I should have spent more time reading the documentation in order to better formulate my questions. 

### A quick interlude(overview?) of XML schemas
In case you ever have to do this task, here’s a brief description of it. First of all, in order to create this one result file (called the flattened file–I made the mistake of not researching using this term), you need to first find the root file. This root file essentially is the heart of the flattened file and calls for other components to build itself up. Or to put it another way, the flattened file is a template for a hamburger. However, each component of the hamburger (buns, lettuce, tomato, etc) have components of their own. So currently at my internship, I’ve been using recursion to start from the root file and gather all of the components from their proper files.
## Examination of questions on Stack Overflow
 
As many programmers will attest, Stack Overflow can really be your lifesaver. It’s amazing how a community of askers and answerers can make an environment to help people learn from other people’s struggles. However, the amount of time knowledgeable people can dedicate to answering questions is extremely limited so through the torrent of questions asked on Stack Overflow, they have to weed out the questions they don’t think are worth answering. As Eric Steven Raymond says in his [article](http://www.catb.org/esr/faqs/smart-questions.html) about smart questions, “We [answerers] take time out of busy lives to answer questions, and at times we're overwhelmed with them. So we filter ruthlessly.”

### Regex
Below are two questions from Stack Overflow, demonstrating a smart and not so smart question. Both regard Regex (**Reg**ular **Ex**pression), which is essentially like a language itself that can help you form a “net” that only captures certain characters. It looks a little wonky (e.g. ``), but with practice, you’ll understand it. 

### A not so smart question
Here, user Tamil.S asks a question to get a RegEx for accepting only characters in the alphabet and has between 2 to 5 characters. However, Tamil.S only specifies what they want in their title: “Regular expression for accepting only alphabets and within 2 to 5 char length” and never restated the question again within the post itself. Instead, their post just looks like this:
```
For example:
Accept:
 - `text`
 - `Text`
Don't accept:
 - `text1`
 - `text@`
 - `123@#`
 - `Te12$`
 ```

While test cases are helpful, this forces answerers to look at the title which can be annoying. However, what’s really bad about this question is that Tamil.S doesn’t demonstrate whether they’ve attempted to solve this problem and what worked or didn’t work. This makes people less inclined to answer because they for one, don’t know which part you’re exactly stuck at and for another, makes the asker appear lazy and not serious about the question. Luckily, kindhearted user Michał Perłakowski tried to answer Tamil.S’s question. We can tell that Michal is a seasoned answerer because not only did he give an answer, but he also created an embedded code snippet that allows Tamil.S to see the code in action. However, if we look closer at Tamil.S’s replies to Michal’s answer, I definitely feel like Tamil could’ve been nicer and more thankful. Additionally, he gives replies that aren’t very helpful (e.g. “I want my input string allow only alphabets and accept 2 to 5 char length.”) and in the end, even though Michal asked for Tamil.S.’s entire code, he didn’t. This is problematic because one advice Raymond has is to “provide a way to *reproduce the problem in a controlled environment*.” to make it easier for answerers to help. What happened in the end? Michal stopped responding and probably determined that trying to answer this question wasn’t worth his time anymore. Lastly, this question has actually been answered on Stack Overflow before. Therefore, Tamil.S. didn’t even try to solve this problem on their own and just quickly fired off a question onto Stack Overflow. 
