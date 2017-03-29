---
##### Variables for repo managers only!

published: false
layout: definition

figure:
	- fig-slug: placeholder
	- alt: Placeholder image.
	- caption: Candidate for a custom figure?

##### Variables that must get values when new file is created.

issue-id:
term:
term-slug:

##### Variables that must get values before definition can be published.

summary: 

meta-description: 

tags: #skip tags for now

collaborators:
  - who: First Last
    affiliation: Entity Name
    affiliation-url: https://content-strategy-forum.github.io/csf-glossary/{{term-slug}}.html 


###### Don't accidently remove the following 3-hyphen line, which terminates the front matter.
---

<h1 class="term-title">{{page.term}}</h1>

<p class="summary">{{page.summary}}</p>

<section class="contributors">
	{% include writers.html ref="{{page.collaborators}}" %}
</section>

<!-- PRIMARY PARAGRAPH(S) OF DEFINITION -->

First para for primary term's explanation. Add the footnote reference number 
on the most applicable sentence related to referenced source.<sup class="ref">1</sup> Yadda yadda.

Or simply use the reference number at the end of a full paragraph, if appropriate.<sup class="ref">2</sup>

Use multiple paragraphs, if needed. 

Somewhere in relation to the primary explanation might be a figure.

<!-- FIGURE (REMOVE CODE IF NOT NEEDED) -->
{% include figure.html ref="{{page.figure}}" %}

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
