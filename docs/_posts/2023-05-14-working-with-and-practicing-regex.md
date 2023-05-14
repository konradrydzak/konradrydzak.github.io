---
layout: post
title: Working with and practicing regex
date: 2023-05-14
---

Whether you want to learn about [regex](https://en.wikipedia.org/wiki/Regular_expression), are already using it, or are 
trying to master this ancient magic of pattern matching (for... reasons)  
![regex superhero](https://imgs.xkcd.com/comics/regular_expressions.png)  
I'll guide you through some tools for learning, testing, and practicing while having fun!

### For beginners and to refresh the material

The best learning sites in my opinion, always have a few things in common:
- are easy to read and understand, 
- have short chapters, paragraphs or sections to learn,
- are interactive in some way. 

With that in mind, I can show you a great example of exactly that: [RegexOne.com](https://regexone.com/).

> And it's sister: [SQLBolt.com](https://sqlbolt.com/) for learning... SQL.

It covers a wide variety of topics, starting small and going all the way to advanced features.  
Seriously, give it a try, I can guarantee you won't realize how fast time has flown by the time you finish the last lesson. 

### Try it out for yourself

Once you've mastered the basics, the best way to get started is to actually use the new tools for whatever you may need. 
Fill in the blanks every time you are struggling with a new problem while you are heavily testing your ideas with an easy to use online tool:
[regex101.com](https://regex101.com/).  
I use it with Python selected, text to be parsed inserted as a test string (sometimes with additional flags set: e.g.: dot as newline) and my initial idea for regex placed. 
The results are live and easy to check, and a quick reference guide will help you every step of the way if you need any tips. 
There you can also see if you find anything new and useful (for example, check out positive/negative lookahead/lookbehind, it's really useful in some cases). 

### Homework, but fun

Last but not least, if you feel the need to challenge yourself and actually measure your knowledge, I can point you to:
[Regex Crossword](https://regexcrossword.com/). As the name says: it's just a crossword with regex, simple but great!
You'll get the hang of it if you start with the tutorial and then work your way through the levels. 
I recommend logging in to save your progress, and checking the settings for any improvements to your experience. 
> I'm just sad that the creators decided to go with a new mobile look, instead of the old traditional website 
> (you can search online to see what that looked like if you're curious).

<br>

I'll leave you to it now with an inspiring quote from Master Yoda: ***"Do or do not, there is no try."***.
```pythonregexp
\b(r\D{2}\S{2})\W( ).*?([^dy\ ]{6}).*?(\,)\ .*?(.{3})\Sself\n.*?([ ]).*?(\w+)(?= [olive]{4}).*?g[ear]{3}t(.)
```
