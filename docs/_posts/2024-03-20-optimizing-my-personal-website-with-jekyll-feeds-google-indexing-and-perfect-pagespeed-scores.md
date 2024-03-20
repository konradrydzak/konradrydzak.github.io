---
layout: post
title: Optimizing my personal website - with jekyll, feeds, Google indexing, and perfect PageSpeed scores
date: 2024-03-20
---

Recently, while updating the content and theme of this website, I've got the urge to undertake a more behind-the-scenes overhaul of it. 
I knew I had a few improvements waiting to be implemented and saw a few areas where I lacked the knowledge to make better use of the available features of the static website generator. 

### Embracing jekyll and bundler gems

First of all, for any test feature development, I would need a place to see the results without having to upload the code to git every time and wait for the GitHub page to rebuild each time. 

Silly me, I didn't look into it more before, so finally (even though I've been using jekyll theme all this time) I turned to having a more efficient website building process. 
By [installing](https://jekyllrb.com/docs/installation/) and [using](https://jekyllrb.com/docs/step-by-step/01-setup/) [jekyll and bundler for gems](https://jekyllrb.com/docs/ruby-101/) I have streamlined my development workflow and gained more control over the structure and content of my site (*by finally being able to **serve** the website locally for my development*). 

> After setting up the project website, use: `bundle exec jekyll serve` to run it on a local web server. 
> 
> If you don't want to rebuild it every time, use `serve --livereload` at the end - it will refresh with every change in the files. 
> 
> After testing, to have the build ready to be shipped use `bundle exec jekyll build` - if you don't do that, all the URLs will point to [http://localhost:4000]() instead of [https://yourawesomewebsiteurl.github.io]()! 

After lying the groundwork for a more dynamic and feature-rich website, we can go to implementing new features! 

### Improving content distribution with feeds

I'm not that into using feeds, maybe I'm not that old to be growing up with RSS, but I have to say that having the ability to access them on my site could not only improve accessibility, but also improve the discoverability of my content across different platforms and devices.  

> It's always nice to be welcoming and open to everyone! 

That being said, I've incorporated JSON, XML and RSS feeds into my website - **look at the sidebar!** By providing structured data in multiple formats, I've ensured that visitors can access and engage with my content in the way they prefer. 

### Adding search engine visibility and indexing

When I first put my website online, I quickly realised a crucial missing piece: it wasn't even indexed by search engines like Google! So unless you came directly to the site via a link, you'd never know it existed.   

To change this, I quickly implemented essential elements such as `robots.txt` and `sitemap.xml`, which are essential for guiding web crawlers to navigate and index website pages effectively. 

By recognising the importance of search engine optimisation (SEO) and incorporating these essential files, I've unlocked the potential for my website to be [discovered and ranked in search engine results](https://www.google.com/search?q=konrad+rydzak+personal+website). This is actually a significant milestone, it allows my content to reach a wider audience and increases its relevance in online searches.

### Elevating accessibility ratings and achiving perfect PageSpeed Scores

As I mentioned earlier, it is always nice to be welcoming and open to everyone! To back up my words, once I'd allowed my site to be searchable online, I set about making sure that the site's performance, accessibility, best practices and SEO were as good as possible.  

Finding out that [Sidey jekyll theme](https://github.com/ronv/sidey) is already great in this regard was extremely helpful. Just a bit of html and css work after my changes for dark mode, and fixing the positions of new features on the site allowed me to get a perfect **4x100/100** score on Google PageSpeed Insights, both on [desktop](https://pagespeed.web.dev/analysis/https-konradrydzak-github-io/l4m52u9rol?form_factor=desktop) and [mobile](https://pagespeed.web.dev/analysis/https-konradrydzak-github-io/l4m52u9rol?form_factor=mobile)!

### Conclusion: a Website transformed

I'm really happy to have gone through my personal website transformation. It's been a nice journey of learning, experimenting and finally - great satisfaction.  
With jekyll as the foundation, feeds for content distribution, SEO essentials for discoverability, improved accessibility for inclusivity, and blazing fast performance for optimal user experience, I'm proud to present a website that somehow sets the bar for greatness - *at least for me!* 

Stay tuned for more updates and improvements as I continue to refine and enhance my online presence. 
