=== IMDBi ===
Author URI: http://iazami.ir
Contributors: mhazami
Tags: imdb,movie information,series information,imdb info,auto imdb,automatic imdb info,auto movie info,movie poster,movie detail,movie,serial,tv,film,cinema
Requires at least: 4.4.0
Tested up to: 4.6.1
Stable tag: 4.4.2
Verison: 2.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

receive movie/series information, including poster and trailer from IMDB.

== Description ==

With this plugin installed, you could get information about movies / series you want, and use them in your posts by shortcodes or in your own template using functions.
Note that this plugin doesn't have any templates packed in, you have to create a template if you want to ([Function Reference](https://github.com/iazami/IMDBi/wiki/Function-Reference)
 - [Sample](https://github.com/iazami/IMDBi/wiki/Sample)).

Features of plugin include:

* Ajax Searching.
* custom poster size.
* editable search results.
* store informations as meta box.
* display informations using shortcode.
* Using thumbnail when poster is not available.
* Uploading poster automatically via url and save it as thumbnail.

= Languages =

1. English
2. Persian (Farsi)

= Notes =

This plugin is not endorsed by or affiliated with IMDb.com

Would you like to help translate the plugin into more languages? [Here is how!](https://github.com/iazami/IMDBi/wiki#translations)

**Want to report a bug, suggest something, or see an option is missing? Raise an issue on [GitHub issue tracker](https://github.com/iazami/IMDBi/issues/new)**

== Installation ==

Using the Plugin Manager

1. Click Plugins
2. Click Add New
3. Search for `imdbi`
4. Click Install
5. Click Install Now
6. Click Activate Plugin

Manually

1. Upload `imdbi` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress and enjoy :)

== Frequently Asked Questions ==

= So, the script writes its result only in Farsi? =

Not anymore.

= Is the plugin functions name are case sensitive? =

yes.

= what is this? ( nfqq.nvswi2lbblah blah blah.nblk.ru ) =

this is a mirror link that refers to  ia.media-imdb.com (IMDB media server).
and why ?
because of internet restrictions in iran, IMDB media servers are restricted.

== Screenshots ==

1. Explorer
2. Search By name
3. Search results
4. Preview
5. Edit Fields
6. Edit Fields
7. Settings

== Changelog ==

= 2.0.2 =
* bug fixes.

= 2.0.1 =
* new: support custom post type.
* new: obtain movie rank in IMDB top 250 (checkout `rank` parameter).
* new: improve persian translation.
* bug fixes.

= 2.0.0 =
* new: using cURL in case that url-fopen was not enabled.
* new: implement an option to activate/deactivate automatic poster download.

= 2.0.0-beta =
* new: refactor entire source code.
* new: plugin is now available in both english and persian.
* new: improving meta box UI.
* new: uploading poster automatically via url.
* new: custom poster size.
* fixed: search results are now editable.
* fixed: ajax search crashing.
* fixed: crawler crash causes.
* fixed: leaking out data.
* fixed: shortcode issues.
* fixed: imdbi() is now expecting one argument.
* fixed: imdbi('poster') is now only return poster url.
* fixed: imdbi_check() is now expecting meta box name as argument ( eg: imdbi_check('year') ).

= 1.5 =
* Store posters into wordpress upload directory.
* Add shortcode.
* redesign ui.
* Fix bugs.

= 1.4 =
* Store Inforamtion In "wp_postmeta" Wp Table.
* Fix loading Custom Jquery lib.

= 1.3 =
* Fix feedback page.

= 1.2 =
* Fix Addressing Problem.


= 1.1 =
* Fix Addresing Problem.
* Changing Image encoding To "Base64".
* Functions parameters Is Not Case Sensitive.

= 1.0 =
* first relase.

== Upgrade Notice ==

= 2.0.0-beta =
before update to this version, please read [Function Reference](https://github.com/iazami/imdbi/wiki/Function-Reference).
gf