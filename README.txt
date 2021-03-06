
=== Display Yelp Widget ===
 Contributors: msicknick
 Tags: yelp, reviews, review, rating, ratings
 Donate link: https://paypal.me/MSicknick
 Requires at least: 4.0
 Tested up to: 5.0.1
 Stable: trunk
 Requires PHP: 5.6
 License: GPLv3
 License URI: https://www.gnu.org/licenses/gpl-3.0.html


 Displays your business's Yelp rating and reviews.

== Description ==
 The plugin adds a widget that displays a specific business's Yelp rating and review.

== Installation ==
  Upload the Yelp Widget to your WordPress blog and activate it.
  Click on Settings (or go to Settings -> Yelp Widget) and follow instructions to obtain an API Key from Yelp.
  Paste your API Key into the setting field and Save.
  Under Appearance -> Widgets, drag and drop the Yelp Widget into a desired location.
  Enter a title and Yelp business ID, and click Save.
  
== Changelog ==

 = Version 1.2.0 (12/18/2018) =
 * Added the latest WordPress 5.0.1 compatibility
 * Changed plugin text-domain to adhere with WordPress plugin standards
 * Added function to initialize settings on plugin install

 = Version 1.1.0 (12/18/2018) =
 * Added setting for disabling plugin stylesheet
 * Added setting descriptions and used better Settings API practices
 * Added activate and uninstall hooks to delete settings from database on uninstall of plugin
 * Code cleanup

 = Version 1.0.0 (12/18/2018) =
 * Initial release