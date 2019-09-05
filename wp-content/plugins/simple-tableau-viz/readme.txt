=== Plugin Name ===
Contributors: garyhukkeri
Donate link:
Tags: tableau, tableau public, analytics, reports, shortcode
Requires at least: 4.9.8
Tested up to: 5.2.2
Stable tag:
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A simple plugin to insert Tableau Public Vizualizations into a WordPress page. This can be done as a Block, Shortcode or via TinyMCE for the Classic Editor. No frills, no options.

== Description ==

A simple plugin to insert Tableau Public Vizualizations into a WordPress page. This can be done as a Block, Shortcode or via TinyMCE for the Classic Editor.

This plugin will only work for Tableau Public Visualizations.

All you need is your Tableau Public url e.g 'https://public.tableau.com/views/WorldIndicators/GDPpercapita'

Usage:

With TinyMCE Editor Button (Classic Editor):
1. Get your Tableau Public url e.g 'https://public.tableau.com/views/WorldIndicators/GDPpercapita'
2. Edit the page/post you want it on
3. Click the Tableau button in the Editor
4. Paste the url and insert and publish

Manual Shortcode( or Shortcode Block for Gutenberg):
If the url is: http://public.tableau.com/views/RegionalSampleWorkbook/Storms
Then, this is the shortcode:
[tableau url="http://public.tableau.com/views/RegionalSampleWorkbook/Flights"]

Embed Block

1. Under the Embed category, select the Simple Tableau Viz block type.
2. Paste your url in the block and publish

That's it. Your Visualization should now render when you view the page.

== Installation ==

1. Upload `simple-tableau-viz` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==
Coming soon.



== Screenshots ==

1. Adding shortcode manually.
2. Adding viz through Editor.
3. An embedded tableau report.

== Changelog ==

= 2.0 =
* Added support for WP Gutenberg Blocks

= 1.0 =
* First release with TinyMCE button on editor.
