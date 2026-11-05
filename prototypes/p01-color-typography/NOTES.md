# NOTES — P1 · Color + Typography

## Intent
I created a hub website that links to 2 very different pages: one is a campaign page for a fictitious politician, and the other is for a creepy-pasta repository. The prototype tis to show how CSS can help websites to have very different vibes. The audience for that main index is for people wanting to learn more about the importance of CSS design.

## AI use
Copilot Chat in Agent mode.
Command 1: The intent will be to create a hub website that links to 2 very different pages: one will be a campaign page for a fictitious politician, and the other will be for a creepy-pasta repository. By the end it should meet the following requirements:
The site
prototypes/p01-color-typography/ has three pages: index.html (the homepage) and two themed pages, all new, not copies of an earlier Spark.
A nav on every page links all three pages.
The homepage explains each themed page’s palette and fonts, with a reason from the theme for each choice, and shows each page’s contrast results.

Color, on each themed page
Its own palette of 3–5 colors in one format (hex, rgb(), or hsl()), used consistently.
At least one background beyond plain white: a color, a gradient, or an image with a fallback color.
Every text/background pair meets WCAG AA contrast (4.5:1 for body text, 3:1 for large text), checked with WebAIM’s contrast checker. The results are on the homepage.
Color never carries meaning alone: links are distinguishable without color (underline, or similar).
Typography, on each themed page
One or two web fonts of its own, each with a fallback stack ending in a generic family (serif, sans-serif), loading only the weights it uses.
Font sizes in rem (or em where it’s relative to the parent on purpose). No px font sizes.
Body line-height of at least 1.5, and line length kept readable (about 45–75 characters).
A heading hierarchy that’s clear from the type alone, in a logical order (h1 → h2 → h3).
Every Prototype (all three pages)
Landmarks (header, main, footer), and CSS in separate files.
Passes the W3C validator with no errors.
Focus is visible on every link.
Readable at 200% zoom (Cmd/Ctrl +): nothing cut off, overlapping, or hidden.
Linked from your hub under Prototypes. Live pages load.
NOTES.md covers every section, in your own words. Meaningful commits.

Command 2: On each of the 3 pages, they have a link to themselves, which is ultimately borderline useless. Can you replace those links with links to the main index instead, and order the new "home" links to the front of the nav menus?

## Accepted / changed / rejected
I kept the basic layout for each of the sites (as it seemed good), though I did a rewrite of almost all of the text it generated. I also had it replace useless links to the page itself with a link to the main index for manuverabiulity, and had it fix some strange heading alignments

## Dig deeper
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th
I decided to dig deeper on table headers, as I'm not positve I fully understood them. Ultimately, I saw that I did basically understand their function, just learned some more details on how they interact with other code.

## Open questions
I still don't fully understand why the AI "thinks" the way it does; somethings seem really simple but take so much fanagling to fix...