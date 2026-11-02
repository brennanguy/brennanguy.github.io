# NOTES — S04 · Type scale

## Intent
I created a type specimen for the theme that I explored in the s03 theme palette. I the type is supposed to feel very retro while not sacrificing readability.

## AI use
Copilot Chat in Agent mode
Command 1:
The intent is to create a website similar to the s03 index, only instead of focuing on colors, we're exclusively focusing on fonts. The theme is the same as the one in s03 as well, and the text should have a retro feel without sacrificing readability. Eventually, this page will have to meet the following requirements:
sparks/s04-type-scale/ has its own index.html and CSS file, and it’s a new page, not a copy of an earlier Spark.
The page names its theme and shows the type in use: headings at three levels (h1, h2, h3), a paragraph of body text, a quote, a list, and a link.
A “Why these fonts” section on the page gives a reason from the theme for each font, the heading sizes, and the line height.
One web font (for example, from Google Fonts) is linked, loading only the weights the page uses.
Every font-family ends in a fallback stack with a generic family, like system-ui, sans-serif.
Every font-size is in rem (or em for something that should scale with its parent). No px font sizes.
Body text has a unitless line-height of at least 1.5, and text blocks are capped at about 65ch wide.
No box that holds text has a fixed height.
At 200% zoom, nothing is cut off, overlapping, or hidden.
With the browser’s default font size set to 20px, the text gets bigger.
The page passes the W3C validator with no errors.
Your hub index.html links to it under Sparks.
NOTES.md covers every section, in your own words.
It’s committed with a meaningful message, pushed, and the live page loads.
Command 2:
Alright, give me 2 or 3 font pairings for the theme, and their type scalings, without writing any code yet
Command 3:
Fantastic! Alright, using the theme and requirements given and the font selected, make a new one-page type specimen: one web font with a fallback, sizes in rem, roomy line height, and a short “Why these fonts” section that says how each choice fits the theme. Be sure not to use px font sizes, fixed heights on headers or boxes, font links that load every weight, or reasoning that is so broad it could apply to any theme. Also, be sure every font-family has a fallback

## Accepted / changed / rejected
I ended up accepting one of the type specimens it suggestec, as well as some of the content. It did generate some unecessary things that I had it get rid of, and I had it alter the alignment of text and add a Nav menu. In addition, I then rewrote most of the content of the page. 

## Dig deeper
https://developer.mozilla.org/en-US/docs/Web/CSS/font-size
I wanted to know more about how font sizes work, as I haven't messed with it in some time. I think I understand how it works, though

## Open questions
I still don't know why the AI does certain things. It seems to run certain checks, and it tells me everything is good or (sometimes) that it couldn't complete the check