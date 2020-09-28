## STX Youth Soccer Association - Custom Code

This repo keeps track of custom code for this Webflow CMS project.

In the future, this may be deployed with a CDN, but for now these get pasted into Webflow custom code fields, either globally or per-page.

All Javascript here is "vanilla", in hopeful anticipation of Webflow making jQuery optional someday (and for the fun of it).

- Site Navigation Logic
  - dropdown menus
  - re-display nav after scroll
  - display back-to-top button after scroll past 1000px
- IE Warning
- Make all external links open in new tabs (and add rel="noopener noreferrer")
- remove duplicate month names from various event lists throughout site
- handle in-page dropdowns, called side-navs, on various pages throughout site
- apply colored gradient overlays to images with certain classes, so site Editors can easily swap out images through Webflow Editor (would otherwise be covered with ::after overlays, preventing Editors from editing them)