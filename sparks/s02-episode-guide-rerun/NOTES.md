# NOTES — S02 · Episode guide rerun

## Intent
I created the episode guide "rerun," a revamped version of the old episode guide. Like it's predecessor, it serves to briefly inform the reader about the show Merlin and share details about the first few episodes

## AI use
Copilot Chat in Agent mode. 
Command 1:  The intent is an updated version of the episode-guide that is now in the "archive" folder. It will, like the original, inform people of the general premise of the show, as well as list information about the first few episodes. By the end of the spark, the following must be accomplished:
sparks/s02-episode-guide-rerun/index.html exists, with its CSS in a separate .css file in the same folder.
The episodes are in a < table > with a < caption >, and header cells use < th > with scope.
The page has header, main, and footer landmarks and one < h1 >.
Every image (if you use any) has alt text that fits its purpose.
The page passes the W3C validator with no errors.
Your hub index.html links to it under Sparks.
NOTES.md covers every section, in your own words.
It’s committed with a meaningful message, pushed, and the live page loads.
Command 2: Model the new documents after their respective counterparts from the archive/episode-guide folder, but feel free to rebuild or improve it. Do not, however add any new information to the new table. Also, be sure that said table properly utilizes < caption > and scope. use < div >s only when strictly necessary, and keep all css within the new stlyesheet.


## Accepted / changed / rejected
I accepted the general design that was proposed, but ended up needing to change a few things. Firstly, I wasn't a fan of the mono-green color scheme it used so I had it create a new one using the gold and blue from the original episode guide. It also only transfered the first 5 episodes over at first, so I had to tell it to transfer the rest. It also changed the footer from "Impirical data sourced from IMBd" to "Episode data...," which was incorrect (as the runtime from the about section is also sourced from IMBd). I asked it why, and it said it was because impirical isn't a word. Turns out, it was right: despite being pronounce impirical, the word is spelled empirical. So it was changed to the correct "Emperical data...".

## Dig deeper
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-labelledby
I learned how aria-labelledby works to aid assitive tech.

## Open questions
I think I've got a much better grasp of what's going on and how the Agent works. I'm still not 100% positive I know what aria-labelledby does, but I'm also no expert in assitive tech.
