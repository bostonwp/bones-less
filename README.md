Bones-LESS
==========

**HEADS UP:** For the complete and original "Bones" starter theme for WordPress, please visit **[http://themble.com/bones](http://themble.com/bones)**

## Built-In LESS Compilation & Deployment

This fork of the [Bones WordPress starter theme](https://github.com/eddiemachado/bones) has been enhanced with the [wp-less](https://github.com/sanchothefat/wp-less) module in order to ease development and deployment of stylesheets using [LESS](http://lesscss.org/). Because this fork is LESS-oriented, the SCSS stylesheets have been removed.

### Support for Bones-LESS

For issues relating to the theme's appearance, template files or behavior, please visit the [Bones theme issues page](https://github.com/eddiemachado/bones/issues). For any issues relating *specifically* to the automatic compilation of LESS-based stylesheets, however, hit us with your bug reports right here at [Bones-Less's issues page](https://github.com/bostonwp/bones-less/issues)

## Bones: A Lightweight Wordpress Development Theme

*HEADS UP!!!* Bones & Bones (Responsive Edition) have been merged.

Bones is designed to make the life of developers easier. It's built
using HTML5 & has a strong semantic foundation. It was updated recently
using some of the HTML5 Boilerplate's recommended markup and setup.
It's constantly growing so be sure to check back often if you are a
frequent user. I'm always open to contribution. :)

Designed by Eddie Machado

**License:** [WTFPL](http://sam.zoy.org/wtfpl/). **Are You Serious?** Yes.

Special Thanks to:

- Paul Irish & the HTML5 Boilerplate
- Yoast for some WP functions & optimization ideas
- Andrew Rogers for code optimization
- David Dellanave for speed & code optimization
- and several other developers. :)

To view Release & Update Notes, read the log.txt file inside
the library folder.

## Changelog

### v1.25 update

- updated custom post type page for translation
- added => to responsive jquery
- cleaned up theme tags (which make NO sense, but are best practice, go figure)
- updated html element to match hb5
- fixed echo problem on admin.php
- updated normalize (LESS also had some missing styles so I added them)
- GetComputedStyle fix for IE (for responsive js)
- cleaned up mixins (border radius)
- added translations! (Chinese, Spanish)

### v1.2 HUGE update

- merge responsive version with classic
- remove post title from read more link (it's way too long)
- removed readme.txt (it was pointless)
- organized info for each file called in on the functions page
- added custom gravatar call in comments
- i'm leaving jQuery to a plugin (that way I'm not providing dated jQuery)
- added translation folder
- put everything inside stuff so it's easier to be translated
- added an identifier in each 404 area so you know what template is showing
- remove custom walker. I think that's better left for you guys to do
- fixed some spelling errors
- added some translation options in the comments file
- added role=navigation to footer links
- deleted image.php (who really uses that anyway)
- added sidebar to search.php
- added class to custom post type title
- added link to custom meta box
- removed selectivizr
- updated html elements with new classes for IE
- added new mobile meta tags
- removed pinned site meta tag for IE9
- merged base.css into style.css for one less call in the header
- added styleguide page and styles (oh yea!)
- added nav class to both menus
- removed "Powered by Wordpress & Bones" from footer, because let's face it: we all delete this anyway.
- added button class to submit comment button
- removed html5 placeholder fallback (you should be using Gravity Forms)
- added slug and rewrite to custom post type for easier urls
- renamed the border radius mixins so they were easer to remember
- removed duplicate box shadow mixin
- deleted the plugins.php file
- facebook og:meta can be better handled by a plugin (or Yoast's SEO plugin)
- rel=me can also be handled by SEO plugin or another plugin
- removed author.php (you can use archive.php or add it yourself)
