# NOTES — S06 · Flexbox

## Intent
I created a website for a carnival, using different boxes for easy navigation for families navigating the site.

## AI use
Copilot Chat in Agent mode.
Command 1: 
Go ahead with that plan. The build will be for a carnival, advertising the various attractions to the families interested in it. These are the assignment requirements:
Make a new page laid out with Flexbox: the title and nav on one line, then a row of featured cards that wraps when there isn’t room, each one jumping to its own section further down the page.
The Nov 4 kit update is committed: your repo has .course-kit-version and the /update-kit skill.
sparks/s06-flexbox/ has its own index.html and CSS file, and it’s a new page, not a copy of an earlier Spark.
The header is a flex row: the title on one side and the nav on the other, and it wraps when there isn’t room.
The nav holds a list of at least three links (for example: your hub, your S05 page, your archive), laid out with display: flex and gap instead of inline-block. Every nav link is at least 24 × 24 px.
A row of three to six featured cards uses Flexbox with flex-wrap: wrap and gap. Each card has a heading, a sentence, and a link to its own section further down the page (an id on the section, and href="#that-id").
Below the cards, a short section of new content for each card, each with a heading.
Each card’s link text is different, and says where it goes (“Jump to the Y Mountain trail”, not “Read more”).
No order and no row-reverse or column-reverse: the order you see is the order in the HTML, and Tab follows it.
At 200% zoom, the header and cards wrap instead of overlapping or overflowing.
The Feedback checks run for your last push shows ✅ for this page in both tables, or NOTES.md says what it found and what you did about it.
Your hub index.html links to it under Sparks.
NOTES.md covers every section, in your own words.
It’s committed with a meaningful message, pushed, and the live page loads.
Command 2: Propose a plan to me for the spark before you write any code, including the page’s sections, which elements become flex containers, and in which direction.
Command 3: That plan sounds good. Go ahead, keeping in mind these additional instructions: Keep the order you see the same as the order in the HTML: if you want a different order (newest first, easiest hike first), move the HTML, not the CSS; make sure the cards tab through in the right order; avoid messing with the order, using -reverse direction, fixed px widths, margins on cards instead of gaps, and identical "read more" links; be sure to use flex-wrap so cards don't squash at 200%

## Accepted / changed / rejected
This time I kept almost everything, as the Agent did a pretty good job at generating a functioning and acceptable website. I did change some of the text, had it center the footer, and remove an ugly and unnecessary dividing line

## Dig deeper
https://developer.mozilla.org/en-US/docs/Web/CSS/margin
I learned how the auto margin feature can be used to center p's.

## Open questions
I'm still not 100% positive i understand the mechanics of flexblox, but I understand what it accomplishes.
