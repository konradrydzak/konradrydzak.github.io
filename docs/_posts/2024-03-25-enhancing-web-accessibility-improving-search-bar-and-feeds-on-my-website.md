---
layout: post
title: Enhancing web accessibility - improving search bar and feeds on my website
date: 2024-03-25
---


In my ongoing efforts to enhance the user experience and accessibility of my website, I have recently implemented a number of minor changes. These updates significantly improve usability for all visitors, including those who rely on screen readers and other assistive technologies. 

In this blog post, I'll discuss the updates I've made, focusing on the switch from a static XML feed file to dynamic feed generation using the jekyll-feed plugin and the improvements to the search bar to ensure compliance with web accessibility standards.

### Switching to Dynamic Feed Generation

Previously, my website used a "static" XML feed file for content updates, but this approach had limitations. To improve efficiency, I switched to automated dynamic feed generation using the jekyll-feed plugin. Now, updates are automated, ensuring that visitors always have access to the latest content.

> You can read more about the jekyll-feed plugin on [GitHub](https://github.com/jekyll/jekyll-feed) or get more details on [RubyGems](https://rubygems.org/gems/jekyll-feed/). 

After lying the groundwork for a more dynamic and feature-rich website, we can go to implementing new features! 

### Improving Search Bar Accessibility

The search bar is a vital tool for navigating content, but it turns out that it lacked proper labeling and styling. Because of that, I have added a label to the search bar input field, improving readability for all users, especially those using screen readers. Additionally, I refined the styling to align with the site's design language. You can find what I have changed below:

```HTML
<!-- Before -->
<div id="search-container">
    <input type="text" id="search-input" placeholder="Search...">
    <ol id="results-container"></ol>
</div>

<!-- After -->
<div id="search-container">
    <label for="search-input">Search the blog for:</label>
    <input type="text" id="search-input" placeholder="Enter keywords...">
    <ol id="results-container"></ol>
</div>
```

### Achieving Accessibility Compliance

To be honest, it didn't magically occur to me that the search bar needed proper labelling and style, but reading more about website accessibility introduced me to a variety of tools to assess this.

![WAVE logo](https://wave.webaim.org/img/wavelogo.svg)

I have mentioned a few websites before, but the one that helped me the most today was [WAVE (web accessibility evaluation tool)](https://wave.webaim.org/). It has helped me ensure that my website meets accessibility standards. These changes have eliminated accessibility errors and created a more inclusive and user-friendly experience for all visitors.

### This... does put a smile on my face

Thanks to these updates, my website is now more inclusive and user-friendly. Accessibility remains a top priority as I continue to refine the site tu ensure it's a place where everyone feels valued and empowered to engage with the content. 

> Cheers to a more welcoming online space for all!
