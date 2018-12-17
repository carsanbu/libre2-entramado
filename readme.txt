=== Libre 2.0 ===

Contributors: automattic
Tags: light, black, white, right-sidebar, two-columns, custom-background, custom-colors, custom-menu, custom-header, editor-style, full-width-template, responsive-layout, accessibility-ready
Requires at least: 4.0
Tested up to: 4.2.2
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html


== Description ==

A stylish, classic look for your personal blog or longform writing site. The main navigation bar stays fixed to the top while your visitors read, keeping your most important content at hand, while three footer widget areas give your secondary content a comfortable home.


== Installation ==

1. In your admin panel, go to Appearance > Themes and click the Add New button.
2. Click Upload and Choose File, then select the theme's .zip file. Click Install Now.
3. Click Activate to use your new theme right away.

== Frequently Asked Questions ==

= Does this theme support any plugins? =

Libre 2.0 includes support for Content Options, Social Links, and Infinite Scroll in Jetpack (jetpack.me).

= Does this theme support widgets? =

Yes, a sidebar on single posts and pages, and three widget areas in the site footer throughout. Configure under Customize -> Widgets.

= Does this theme support custom menus? =

Yes, a main navigation area appears in the header, and "floats" over your content as you scroll, keeping your most important content at hand.

= Does this theme have any page templates? =

Libre 2.0 has two page templates for displaying your content in an alternate format. View them in action on the demo site: http://libredemo.wordpress.com

* The Full Width, No Sidebar template is a wide page template, giving your content plenty of space to spread out.
* The Right Content, No Sidebar template mimics the look of the blog, with the page title on the left and the content on the right.

= Does this theme have any special features? =

Libre 2.0 includes styles for introductory text and pull quotes. See how these work on the demo site: https://libredemo.wordpress.com/text-formatting/

Quick Specs (all measurements in pixels)
* The main column width is 739, except on the full-width page template, where it's 1088.
* The main sidebar width is 272.
* The footer widget areas vary in size depending on the number of active areas.
* The site logo appears at a maximum width of 150 and height of 50 in the floating header, and a maximum width of 300 and height of 300 elsewhere.

== Changelog ==

= 22 November 2018 =
* Minor fixes to Gutenberg implementation, including: * Update selectors for buttons, custom colours. * Correct caption styles on front-end and in editor. * Remove spacing around figure elements in editor.

= 19 November 2018 =
* Add overflow x to the html element, to fix an issue with the header causing side-scrolling.

= 7 November 2018 =
* Add Gutenberg support to theme.

= 16 July 2018 =
* Fix Jetpack Infinite Scroll on WooCommerce pages and add misc WooCommerce-related styling

= 27 April 2018 =
* Add support for the new WC 3.3+ Customizer options

= 5 April 2018 =
* Optimize images

= 7 March 2018 =
* Improvements to contact form appearance.
* Add styling for the Payment Methods table on the Pay for order page

= 6 March 2018 =
* Fix My Account buttons spacing issue

= 24 February 2018 =
* Fix the issue with product gallery images becoming taller on hover

= 23 February 2018 =
* Simplify Headstart annotations.

= 21 February 2018 =
* Fix the incorrect WooCommerce image sizes
* Define WooCommerce image sizes

= 15 February 2018 =
* Switch away from ems to pixels in media queries and to define main element's widths, to make sure font size change doesn't impact the layout.

= 27 October 2017 =
* Remove commented-out block of sample header cart implementation.

= 23 October 2017 =
* Add full support for WooCommerce by hooking up the functions file in functions.php and adding the mini cart widget to the header if available. Also updates the post thumbnail handles to match the theme slug, and makes some minor visual tweaks to ensure the header cart fits with the layout.
* Continue adding WooCommerce support in pieces; this includes the functions file and some modifications to IS for Jetpack when WC is enabled.
* Fix minor bug with display of menu when a long tagline/site title are used. This removes the bottom margin and avoids the menu getting pushed down a line.
* Committing WooCommerce specific styles.
* Begin addin support for WooCommerce; adding Genericons icon font.

= 14 September 2017 =
* Update version number
* Prevent the tagline from splitting awkwardly

= 4 July 2017 =
* Adding hover styles for both the social menu and social icons widget. Wanted to cover both for consistency.

= 12 May 2017 =
* Disable word-wrap for post titles in single post view.

= 11 May 2017 =
* Adjust menu width to make sure monospaced fonts don't break the header layout.

= 21 April 2017 =
* Add Smarter Featured Images support, off by default.

= 27 March 2017 =
* Remove custom colors for Sharedaddy as it was removed during review.

= 22 March 2017 =
* add Custom Colors annotations directly to the theme
* move fonts annotations directly into the theme

= 7 February 2017 =
* Replace get_the_tag_list() with the_tags() for a more straightforward approach that prevents potential fatal errors.

= 26 January 2017 =
* Removing width: 100% from the date and post author as well. Both are display block so should do that anyway; was also causing side-scrolling when those were hidden in Chrome. Actually
* Adding width: auto to the categories and tags when display: inline -

= 20 January 2017 =
* Remove custom styles from sharing icons; they can't be easily overridden and won't work with Custom Colors.
* Calling wrong stylesheet in Content Options.

= 16 January 2017 =
* Ensure comment likes don't have hover/borders
* Add POT file.

= 13 January 2017 =
* Move menu toggle further to the right and reduce the max-width of the site branding area to avoid overlap on mobile devices.
* Don't add link styles to links in the audio playlist; remove decorative border from captions in galleries.
* Make sure textareas get the same box-shadow treatment as other form fields
* Make sure all style and script handles are prefixed with libre-2 rather than libre
* Update text domains and function pre
* Change package headings from Libre 2.0 to Libre 2; rearranges some functions in functions.php and includes a commented-out function for Google fonts preloading that isn't working yet.
* Fix for mobile menu parent items requiring double tap
* Add SVG support for social icons
* Add theme support for selective refresh for widgets.
* Improve comments header for translation purposes.
* Remove hard-coded pingbacks tag from header
* Better styles for button links with .button class.
* Smarter pingbacks; remove from header.php and move to a function hooked to wp_head
* Add header for posts page when static front page is in use.
* Updated skip link focus fix JS

= 12 January 2017 =
* Add tags/categories to blog and archives, and adjust spacing
* Use currentColor rather than hard-coded HEX values to better work with Custom Colors.
* Remove incorrect naming of theme in footer credits; Libre 2 instead of Libre 2.0, which was also messing up our footer regex.
* Reducing spacing between older posts button and content for better context; remove box-shadow treatment from JP related post links.
* Reduce top padding a bit; ensure images in content don't get linked hover treatment
* Don't add box shadows on social links in header
* Use box-shadow instead of borders/margins for adjusting bottom borders on links to avoid jankiness with transitions

= 11 January 2017 =
* Update credit information and screenshot
* Update theme name to match slug (2 instead of 2.0); add relevant tags
* Fix mistake with escaped translation string for Sticky posts in entry meta.
* Update screenshot and readme.txt, tweak to spacing.

= 21 December 2016 =
* Fix style of social links on mobile devices
* Remove unnecessary comment-list HTML5 support since I have a custom callback.
* Fix sidebar IDs in footer.php; make sure content is only centered on pages and single posts that aren't the custom page templates.
* Ensure singular content is centered when no sidebar is active.
* Styles for author bio and updated Headstart annotations.
* Update post thumbnail size for full-width page template and make sure content width is adjusted on full-width page template.
* Add three-lines icon to menu toggle; add .button class for links; don't display date for Sticky posts.
* Initial commit to repo.

== Credits ==

* Photo in the screenshot is from unsplash.com, licensed CC0
* Based on Components http://components.underscores.me/, (C) 2015-2017 Automattic, Inc., [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html)
* normalize.css http://necolas.github.io/normalize.css/, (C) 2012-2015 Nicolas Gallagher and Jonathan Neal, [MIT](http://opensource.org/licenses/MIT)
