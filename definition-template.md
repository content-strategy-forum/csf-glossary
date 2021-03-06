---
published: false
layout: definition
issue_id:

###### Term
title:

###### Meta
tags: 
description: 

summary:

###### Writers=Authors. If writer, add your own 4 lines of data. Use spaces, not tabs, to align parameter keys. 
writers:
  - name:
    affiliation:
    affiliation_url:
    country:

###### Reviewers=Editors. If reviewer, add your own 4 lines of data. Use spaces, not tabs, to align parameter keys. 
reviewers:
  - name: 
    affiliation: 
    affiliation_url: 
    country: 

###### Glossary managers use only.
figure:
  fig_slug: placeholder 
  fig_alt: "Alt text for placeholder image."
  fig_caption: "A belle figure of mysterious nature."
---

<h1 class="term-title">{{ page.title }}</h1>

<p class="summary">{{ page.summary }}</p>

<!-- COLLABORATORS – This must not move nor be deleted -->
{% include authors.html %}

<!-- PRIMARY PARAGRAPH(S) OF DEFINITION -->

First para for primary term's explanation. Add the footnote reference number 
on the most applicable sentence related to referenced source.<sup class="ref">1</sup> Yadda yadda.

Or simply use the reference number at the end of a full paragraph, if appropriate.<sup class="ref">2</sup>

Use multiple paragraphs, if needed. 

Somewhere in relation to the primary explanation might be a figure.


<!-- FIGURE – You can move this line to position among paras, but never delete it! -->
{% include figure.html %}


<!-- EXAMPLE(S) -->

Use a new paragraph for each real-world example.<sup class="ref">4</sup> 

Each example should reference a source, unless theoretical.<sup class="ref">5</sup>

<!-- SIMILAR TERMS EXPLAINED, IF ANY -->

Use a new paragraph for each mention of a similar term. Similar terms are what we include in the glossary index as _secondary_ entries that redirect to the primary entry. So don't include a "similar" term if it's not synonymous with the primary term, or at least close. Any differences for close terms should be explained. Similar terms mentioned must have at least one (different) source reference each.<sup class="ref">6</sup>

<!-- FOOTNOTES REFERENCES -->
<hr class="footnotes">

<ol class="references nomark">
	<li><sup>1</sup>
		F. Last, _[Title of article](url)_, Name of site, Blog, YYYY, (accessed Month DD, YYYY).
	</li>
	<li><sup>2</sup>
		F. Last, _[Title of article](url)_, Name of site, Blog, YYYY, (accessed Month DD, YYYY).
	</li>
	<li><sup>3</sup>
		Et cetera
	</li>
</ol>
