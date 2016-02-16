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
	- Script requests (can see traces of plugins here) - how many are there?
	- How many stylesheets? Also indication of plugins.
	- Inline styles and `div` soup
	- `!importants` and overridden styles
	- Signs of heavy options panels and page builders
	- What is what? Posts vs. page vs. custom post types
	- Check for console errors

3. Performance
	- Run both the demo page and the theme landing page through [webpagetest.org](http://webpagetest.org)
	- Speed index less than 4000
	- Page weight
	- Throttle Network in Chrome
	- Turn off JS - can you still see content?
	- If you have several windows of the theme open, is your fan running like crazy?
	- In the Network tab, how many requests are there and how large are they? Pay attention to stylesheets and scripts in particular.
	- Are the scripts and styles minified? This is something you can take care of, but it is an indicator of quality.
	- [Enable paint flashing](https://developers.google.com/web/fundamentals/performance/rendering/simplify-paint-complexity-and-reduce-paint-areas?hl=en). Does the page turn green when you scroll? That's bad.

4. UX
	- Is the scrolling janky?
	- Does everything animate in and make you want to vomit?
	- Are hover states on mobile disruptive? e.g. thumbnail captions.
	- Are sliders touch sensitive? Does the text resize appropriately?
	- Are there loading icons? Usually is an option to turn these off, but still...try throttling the network to 3G and you'll see what I mean.

### Opinionated Recommendations

1. Do not use those counter things.
2. Disable loading icons.
3. Do not use Revolution Slider or any of those gigantic sliders.
4. [Scroll-Jacking](http://robinrendle.com/notes/scrolljacking/) should die.
5. You don't need parallax.
6. One video background per page, please. or better yet...zero.
	
## Resources

I don't necessarily condone everything here, but these are some resources for themes and the like.

### Articles

* [Google Web Fundamentals: Performance](https://developers.google.com/web/fundamentals/performance/?hl=en)
* [Response Times: The 3 Important Limits](https://www.nngroup.com/articles/response-times-3-important-limits/)

### Theme Shops

* [Mighty Themes](http://meetmighty.com/)
* [Theme Foundry](https://thethemefoundry.com/)
* [Graph Paper Press](http://graphpaperpress.com)

### Theme Repositories that are not Theme Forest

* [WP Explorer](www.wpexplorer.com/wordpress-themes/)
* [WP.org Commercial Theme Repo](https://wordpress.org/themes/commercial/)...maybe.

### Frameworks

Child themes are great, but keep in mind there are no *grandchild* themes, so if you use a ready made child theme you won't be able to create a child theme. So meta...

* [Make](https://thethemefoundry.com/wordpress-themes/make/), Theme Foundry
* [Canvas](www.woothemes.com/products/canvas/), WooThemes
* [StudioPress](http://www.studiopress.com/)

### Speed Testing Tools

* [Webpage Test](http://www.webpagetest.org)
* [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/)
* [YSlow](http://yslow.org/)

### Useful Plugins and Services

I do condone these!

* [EWWWW Image Optimizer](https://wordpress.org/plugins/ewww-image-optimizer/)
* [WP Super Cache](https://wordpress.org/plugins/wp-super-cache/) (but note many big themes come with their own caching)
* [WP Offload S3](https://deliciousbrains.com/wp-offload-s3/)
* [Cloudflare](http://cloudflare.com)


