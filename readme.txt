=== WordPress Admin Bar ===
Contributors: Viper007Bond
Donate link: http://www.viper007bond.com/donate/
Tags: admin, bar
Requires at least: 2.7
Tested up to: 3.0
Stable tag: trunk

Deprecated / dead plugin.

== Description ==

This plugin has been deprecated and is no longer being developed. It has been replaced by the admin bar that is now built into WordPress since version 3.2.

== ChangeLog ==

= Version 3.1.12 =
* Fix the generation of URLs to use `&` instead of `?` where necessary. Thanks to lucasm for reporting this.

= Version 3.1.11 =
* The theme editor is added using the API but yet is it's own script. This was breaking the link in the admin bar. Add a manual exclusion for this particular item (ugly, but it works).

= Version 3.1.10 =
* Fix broken dashboard link. Need to check `!empty()`, not `isset()`. Thanks to @LuisTheDude for reporting the issue.

= Version 3.1.9 =
* Update for WordPress 3.0.
* Bug fix for children of custom top-level menu items.
* Italian transation thanks to [Gianni](http://gidibao.net/).

= Version 3.1.8 =
* Don't do anything within the comments popup. Props [spencersokol](http://wordpress.org/support/topic/358681).

And yes I'm aware this plugin will need updating for WordPress 3.0. :)

= Version 3.1.7 =
* PHP notice fixes.
* Added Japanese translation thanks to Naoko McCracken.

= Version 3.1.6 =
Update for WordPress 2.8.

* Moved the settings page to Tools as that menu is available to all users including subscribers.
* Updated the jQuery checkboxes plugin.
* Add a new global to `WPAdminBar::SetupMenu()` to fix a notice and warning about taxononmies. Props rovo89.
* Hide seperators as they aren't true menu items

= Version 3.1.5 =
* Start plugin slightly later so plugins like Gengo that aren't hooking in early enough (use priorities!) can get their stuff done first.
* Notice fixes.

= Version 3.1.4 =
* Fix HTML validation error. Props Flashbytes.
* Add filter to default settings.

= Version 3.1.3 =
* Adjust settings page unordered list CSS for WordPress 2.7 (add some padding to children menu items).

= Version 3.1.2 =
* Make the log out link work correctly (use the function that'll produce a nonce'd URL).

= Version 3.1.1 =
* Version 3.0.3 should have been 3.1.0, so this is 3.1.1.
* Wrap parenthesis around the number of plugins needing updating to make it clearer.

= Version 3.0.5 =
* Forgot to finish making the settings form redirect back to the form after saving. Fixed.
* Don't hide the default navigation menu in the admin area any more even if this plugin is being used there. Just collapse it if you don't want to see it.
* Force some settings page stylings for WordPress 2.7.

= Version 3.0.4 =
* Remove debug code (sorry!).
* Fix a little big.

= Version 3.0.3 =
* Update for WordPress 2.7. No new features or anything, this was just an "emergency" release.

= Version 3.0.2 =
* Fix navigation tabs being hidden in the media uploader.
* Add a link to the Settings page next to the plugin (de)activation link.
* Minor code improvements.

= Version 3.0.1 =
* Fix display issues in IE. Props Mark.
* Don't allow this plugin's menu item to be hidden in the admin area, otherwise it'd be possible to hide all menus and not easily be able to get them back.
* Hide the "Dashboard" tab in the upper-left on non-WPMU installs if the admin bar is enabled in the admin area.

= Version 3.0.0 =
* Complete recode from scatch. Changes too many to list (themes, options page, etc.)

= Version 2.0.5 =
* `position: fixed` made the cursor not show up in input boxes. The default has been changed to `position: absolute` which means it will no longer stick at the top of your screen when you scroll.

= Version 2.0.4 =
* Some CSS added in 2.0.3 hides the comments in moderation count if it's 0, but the plugin was still adding parathensis regardless. This has been fixed.

= Version 2.0.3 =
* Added a tweak to put parathensis around the comments in moderation count in WordPress 2.5.
* Some CSS, image, and code improvements.

= Version 2.0.2 =
* Need to include_once() rather than include() to avoid having all menu items being listed twice in the admin area if this plugin is enabled there. Props Nigel Kane.

= Version 2.0.1 =
* Support added for using this plugin in your admin area. Just edit the plugin file and uncomment the two hooks as described in the file.

= Version 2.0.0 =
* Plugin renamed to "WordPress Admin Bar" to avoid any confusion that this plugin is officially related to WordPress.com.
* Complete recode from scratch. Everything is dynamic now and pulled directly from the regular admin area.

= Version 1.0.3 =
* Support for Democracy added as well as the upcoming WordPress v2.1.

= Version 1.0.2 =
* Support for more plugins added, including Akismet (thanks Paul for reminding me).

= Version 1.0.1 =
* All CSS declarations in the CSS file are now marked as !important to make sure to overwrite your theme’s declarations and make the admin bar display correctly.

= Version 1.0.0 =
* Initial release.