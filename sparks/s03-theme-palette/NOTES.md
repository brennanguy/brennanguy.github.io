# NOTES — S03 · Theme palette

## Intent
I built a theme palette for a fictitious shadowy organization of superheroes seeking to defend the world against the return of ancient powerhungry gods. In universe, I think it's funny to imagine the organization having a brand manager who makes sure that their uniforms and secret website use a consistent color pallete, and this site would be for said person to refer to.

## AI use
Copilot Chat in Agent mode. 
Prompt 1: The intent is to create a theme for a shadowy secret organization for superheroes seeking to defend the world against the return of ancient powerhungry gods. It must fulfill the following criteria:
sparks/s03-theme-palette/ has its own index.html and CSS file.
The page has a heading on a linear-gradient(), a short “about this theme” paragraph (3–4 sentences), and four palette cards: page background, text, accent, and highlight.
Each card shows a swatch, the color’s name, its role in words, and its value written three ways: hex, rgb(), and hsl(). The three match.
The CSS file lists the palette once at the top, in one of those formats, with a comment naming each color.
The page includes a paragraph of sample text, an underlined link, and a button, all in your palette.
A contrast table on the page lists every text and background pair you use, its ratio from the WebAIM contrast checker, and a word for what it’s good for: “Body text” or “Large text only”.
Every body text pair is at least 4.5:1, and every large text pair at least 3:1. The heading passes at the gradient’s worst point.
Focus outlines are visible on every background, and nothing relies on color alone: roles and results are written in words.
The page passes the W3C validator with no errors.
Your hub index.html links to it under Sparks.
NOTES.md covers every section, in your own words.
It’s committed with a meaningful message, pushed, and the live page loads.
Prompt 2:
I will need 4 colors, and each must have a specific role and all relevant contrast ratios. Be sure to calculate all the ratios and make sure that the hex, rgb, and hsl values all describe that specific color.
Prompt 3:
Go ahead with the expanded plan using the above colors. While doing so, be sure not to remove text decoration on links, be sure all focus outlines remain visible against the background, and be sure the heading is readable at all points on the gradient

## Accepted / changed / rejected
I kept most of the basic outline it gave me, as well as the colors it selected. It did try to jump the gun and generate the code when I asked for the colors pallette, so I had to clarify myself. In addition, i replaced/revised practically all of the text in the "about this theme" section as well as in a few other places. I rejected an odd section that wasn't necessary that contained the button and "reveiew the palette" link, moving the Review the palette into a new nav menu, adding the link home, and creating the new Contact Information button and subsequent gag as, apparently buttons don't work without JavaScript.

## Dig deeper
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button
I did not remember much of anything about buttons or how they worked, especially that they do not work without JavaScript

## Open questions
I'm not gonna lie, I still don't understand why we were asked to make a button when said button will not function, but I'm sure that'll make sense later in the course
