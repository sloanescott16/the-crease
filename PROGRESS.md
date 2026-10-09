# PROGRESS - classic-stars (job 1009-1116-ne2)

- Stage 1 (done): classic Stars logo saved in img/ from the NHL logo CDN (see img/STARS-LOGO-SOURCE.md).
  Swapped in for the tab icon, the top-bar logo, and every Stars logo drawn through logo()/onErr(). Version v33.
- Stage 2: before and after screenshots at desktop and phone widths in preview/.
- Stage 2 (done): screenshots in preview/, taken with headless Chrome over the DevTools protocol against live ESPN data
  (local http server, normal browser user agent, since ESPN refuses HeadlessChrome). before-* is main, after-* is this branch.
  *-desktop / *-phone: home a few seconds in (top-bar logo); *-loaded-*: home fully loaded (top bar, Next Up hero, tale of the tape).
  Desktop 1440x900, phone 390x844.
