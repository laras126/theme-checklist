Note: be sure to X out any theme preview header thing.

Does it use:

* A page builder?
* A monster slider plugin?
* Custom post types?
* Are there plugin dependencies?
* Monster options panels?
* A loading icon...bad.
* Icon fonts (not ideal)


Does it have:

* Good documentation
* Good support
* Read the support forum, are there helpful answers?
	* What response time?
	* Are they detailed answers?
* A reputable developer
* An incredibly annoying pop-up during the theme demo, [like this]()


Take into account:

* Is it a child theme? Limiting when it comes to code customizations. Cue Genesis.
* Date of last update
* Number of downloads
* Listed browser compatability
* Is it a single developer or a theme shop? Can't always tell which is which
* What's a page, what's a post, and what's an archive? Looking at the body classes.


Don't necessarily take into account:

* Theme ratings
* Theme reviews


Code:

* Are there inline styles?
* Are there traces of a page builder?
* How many stylesheet and script requests are there?
* Are they coming from plugins?
* Are scripts loaded in the footer?
* [W3C Markup Validator](https://validator.w3.org/)
* Are there scripts within the markup?


Slowly resize the browser:

* Does text overlap or become unreadable?
* Do image dimensions still make sense?
* What does the menu look like?
* Characters per line - often there are way too many at large screen sizes


Testing:

* Webpagetest.org: Speed index under 3000
* Check for console errors
* Turn off JavaScript. What's there?
* Throttle connection in Inspector
* Is there a FOUT (good) or is text hidden when you load the page?
* How big is the page? Open the Network tab in Inspector and refresh. 


Features I am generally opposed to:

* Scroll jacking
* Video backgrounds everywhere
* Every single thing animating in as you scroll down the page
