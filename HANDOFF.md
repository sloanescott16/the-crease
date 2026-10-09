# HANDOFF - classic-stars (job 1009-1116-ne2)

What: every Dallas Stars logo in The Crease is now the classic 1994-2013 mark (NHL logo CDN, local copy in img/, source in img/STARS-LOGO-SOURCE.md). Version v33.
Where: tab icon (img/stars-classic-256.png), top-bar logo (#favLogo), and logo()/onErr() for ESPN NHL id 9 or abbreviation DAL, which feeds every team logo on the site.
Run: serve the folder over http (ESPN refuses file:// and HeadlessChrome), open index.html.
Test: Stars logos (top bar, Next Up hero, tale of the tape, standings) show the green and gold star with "DALLAS STARS"; other teams unchanged. Compare preview/before-* and preview/after-*.
Unsure: the classic mark is wider than tall, so in the square slots it fills the width and reads a little smaller than the old square logo. Not pushed or merged.
