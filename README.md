# The Premium Theme Checklist

First and foremost: **Plan nothing**. The fewer preconceived notions of layout and content stucture you have, the better. 

Do not work from a layout. Work from the theme first and map your content to the demo one-to-one as best you can.

### How to test

1. When you open the theme demo, first remove the frame at the top. You may need to Inspect Element and find the iframe source.
2. Select a specific demo site rather than the splash page. For example: Avada for Travel, [X for Church](http://theme.co/x/demo/expanded/church/)...or something like that. That is the demo content you will use.
3. Make sure demo content is included with theme download. 
4. As you vet, think "do I have content for that section"?

### Credibility

On the Themeforest page, check for:

1. Last updated vs. original upload
2. Documentation
3. Number of downloads
4. Developer credentials

### Testing

1. Responsiveness - open in Inspector
	- Characters per line on large screens
	- Open device view in Inspector, or use simulator
	- Child menu items
	- Image dimensions on small screens
	- Do sliders hold up?
	- LOOK AT IT ON YOUR PHONE (or [a simulator](http://bavotasan.com/2012/set-up-an-ios-simulator-on-a-mac/))

2. Code
	- Script requests (can see traces of plugins here) - how many? Are they in the footer?
	- How many stylesheets? Also indication of plugins.
	- Inline styles (`background-image` is excusable)
	- Plugins
	- `!importants` and overridden styles
	- Signs of heavy options panels and page builders
	- What is what? Posts vs. page vs. custom post types
	- Check for console errors

3. Performance
	- Run both the demo page and the theme landing page through [webpagetest.org](http://webpagetest.org)
	- Speed index less than 4000
	- Page weight
	- Throttle
	- Turn off JS - can you still see content?
	- If you have several windows of the theme open, is your fan running like crazy?
	- Is there a FOUT? Doubtful, but that would be great.
	
4. UX
	- Is the scrolling janky?
	- Does everything animate in and make you want to vomit?
	- Are hover states on mobile disruptive? Think: thumbnail captions.
	- Are sliders touch sensitive?
	- No loading icons (usually is an option to turn these off, but still...)

### Opinionated Recommendations

1. Do not use those counter things.
2. Do not use Revolution Slider or any of those gigantic sliders.
3. [Scroll-Jacking](http://robinrendle.com/notes/scrolljacking/) should die.
4. You don't need parallax.
5. One video background per page, please. or better yet...zero.
6. Learn how to build your own site.
	
## Resources

### Articles

* [Trustworthy WordPress Themes](http://chrislema.com/trustworthy-wordpress-themes/), Chris Lema

### Theme Shops

* [Mighty Themes](http://meetmighty.com/)
* [Theme Foundry](https://thethemefoundry.com/)
* [Graph Paper Press](http://graphpaperpress.com)


### Theme Repositories that are not Theme Forest

* [WP Explorer](www.wpexplorer.com/wordpress-themes/)
* [WP.org Commercial Theme Repo](https://wordpress.org/themes/commercial/)...maybe.

### Useful Plugins

* [EWWWW Image Optimizer](https://wordpress.org/plugins/ewww-image-optimizer/)
* [WP Super Cache](https://wordpress.org/plugins/wp-super-cache/) (but note many big themes come with their own caching)
* [WP Offload S3](https://deliciousbrains.com/wp-offload-s3/)

### Frameworks

Watch out for child themes, or at least know what you're getting into (i.e. there are no *grandchild* themes).

* [Make](https://thethemefoundry.com/wordpress-themes/make/), Theme Foundry
* [Canvas](www.woothemes.com/products/canvas/), WooThemes
* [StudioPress](http://www.studiopress.com/)
