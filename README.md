# Kitty Cat (installable app)

Host this whole folder on any HTTPS site, then install it from the browser.
Easiest free options: Netlify Drop (drag the folder onto app.netlify.com/drop)
or GitHub Pages (push to a repo, enable Pages).

Install:
- iPhone: open the URL in Safari > Share > Add to Home Screen
- Mac (Safari): File > Add to Dock
- Mac (Chrome/Edge): click the install icon in the address bar

Works offline after the first visit. To ship an update, replace index.html;
it appears on the next launch. Bump CACHE in sw.js if you change the icons.

Note: saved progress lives in the browser for this site's address, so it
starts fresh compared with the claude.ai version, and each device keeps its own.

How it works: same block game as Times Tables, but each board has a CAT4-style
rule picked by the wheel — Word Groups, Word Pairs, Secret Number Rule,
Shape Rule, Mirror Twins and Turn Twins. Bonus questions and the 5-question
New Board gate are CAT4-style multiple choice (all eight CAT4 question types),
and a wrong answer explains why before asking again. Boards and questions get
harder as the level goes up. Settings (⚙️) choose which boards appear.

CAT4 is a trademark of GL Assessment. Kitty Cat is not affiliated with or endorsed by GL Assessment.
