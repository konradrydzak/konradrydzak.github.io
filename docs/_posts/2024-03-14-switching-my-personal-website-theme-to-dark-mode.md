---
layout: post
title: Switching my personal website theme to dark mode
date: 2024-03-14
---

Every now and then I take a quick look at my portfolio, resume, LinkedIn, GitHub, all my project websites to check if everything is up-to-date and working.
Yesterday, while checking this page, I had a 💡 moment. 

> Or rather, my eyes hurt from seeing all the white brightness of the default [Sidey jekyll theme](https://github.com/ronv/sidey).

### Join me on the dark side...

I prefer to use dark mode whenever I can (sue me!), so I thought I'd try to switch to it for my website. I thought "how hard can it be? just a few *css* color properties to change/set and all will be well...". Now I know how naive that was!

But don't get discouraged, it's really not that hard (***if you know what you're doing*** 😉). 

And to help you out - see how the difference is like night and day (but reversed):

![Sidey jekyll original light mode theme](/assets/images/Sidey-jekyll-light-mode-theme.png)
![My custom Sidey jekyll dark mode theme](/assets/images/Sidey-jekyll-dark-mode-theme.png)

### Changing Cascade Style... Oh, no! Now everything is black *or* white - not inverted!

What's the easiest way to find out what colors a website uses? Of course, **not** reading the *docs/_sass/_main.scss* file first is the best way to start...
But in all seriousness, simply going to the site and hitting 'Inspect' is quick, clever and easy. A few attempts of changing the hex or rgb values found, and we're golden. 

> As a side note, I highly recommend not using pure black as a background - it's just weird.
> What I'm using here is *#121212* for example, just a little bit off **black** works wonders. 

### Everything is fine and dandy, so where's the catch?

We've figured out what to change, experimented with some color values that look nice, gone back to the *css* file, formatted it, changed every color/background/CTRL+F: '#' or 'rgb(...)'. 
Now just commit all of it, push it to a "style-testing" branch, build, deploy and see it in all it's glory!

But wait a minute, Blog(s) are good, About me and Contact is fine, but what's up with the Search bar being so bright all of a sudden?

If you want, you can check the commit history to see how I blatantly pasted a fixed input style for the search bar into my website's (mentioned everywhere) *css* file. 
Surprise, surprise - it didn't work. Silly me spent half an hour finding out that the *docs/_pages/search.md* file had set input style inside!
One line quick fix, and we're merging to main. 

### Victory! But what's that? You don't like it? Hmmm...

Yes, I know: not everyone prefers the dark mode, and I understand that. I'm not forcing my opinion on you, or rather ***technically*** I am for the time being, but I promise: if there is a day when I will visit my website, find the energy, courage and a working monkey brain inside me to figure out how to add a toggle to switch between light mode and dark mode - I will do it for sure!

<br>

> By the way: Happy Pi-Day! 🥳
