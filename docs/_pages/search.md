---
layout: page
title: Search
---

<style>
	#search-container {
        margin-top: 0.7rem;
	    max-width: 100%;
	}
    label {
        margin-bottom: 0.5rem;
        display: block;
        font-size: 1.17em; /* Equivalent to Markdown heading level 3 (###) */
        font-weight: 600; /* Make the text less bold */
    }
	input[type=text] {
		font-size: normal;
	    outline: none;
	    padding: 1rem;
		background: #333;
	    width: 100%;
		-webkit-appearance: none;
		font-family: inherit;
		font-size: 100%;
		border: none;
	}
	#results-container {
		margin: .5rem 0;
	}
</style>

<!-- Html Elements for Search -->
<div id="search-container">
<label for="search-input">Search the blog for:</label>
<input type="text" id="search-input" placeholder="Enter keywords...">
<ol id="results-container"></ol>
</div>

<!-- Script pointing to search-script.js -->
<script src="/search.js" type="text/javascript"></script>

<!-- Configuration -->
<script type="text/javascript">
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json',
  searchResultTemplate: '<li><a href="{url}" title="{description}">{title}</a></li>',
  noResultsText: 'No results found',
  limit: 10,
  fuzzy: false,
  exclude: ['Welcome']
})
</script>
