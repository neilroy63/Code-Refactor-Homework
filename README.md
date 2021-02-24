# Overview 

The challenge was to improve an existing codebase to ensure that the resultant web site followed accessibility standards and was optimized for search engines. 

# Design Decisions 

The architecture was relatively simple as I was given an existing codebase to work with. 

My decisions were principled on [Semantic HTML.](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility)

Bearing this in mind, I concentrated on giving semantic meaning to the HTML and condensing the code in the CSS stylesheet. 

# Issues 

The main issue with the HTML was due to the oversue of generic div elements without proper labelling to correspond with the structure or sections of the page. 

Minor issues with the h1 tag and internal linking was also identified and remedied. 

The CSS stylesheet suffered from bloated code due to unecesssary duplication so I consolidated the selectors which had identical properties. I also organized them with appropriate commentary to follow the semantic structure of the HTML.

# Assumptions 

I have assumed that the challenge was purely an exercise in improving the existing codebase from an accessibiltiy perspective. 
