=== Toggle Meta Boxes ===
Contributors: dsader
Donate link: http://dsader.snowotherway.org
Tags: dashboard, network, multisite, toggle meta boxes, edit form, edit, media buttons, quick edit,
Requires at least: 3.8.1
Tested up to: 4.6
Stable tag: Trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A Multisite Network plugin to toggle administration meta boxes for the entire network of sites.

== Description ==
A [Multisite](http://codex.wordpress.org/Create_A_Network) Network plugin. Go to Network-->Settings to "Enable Administration Meta Boxes". Meta boxes(post, page, link, menu, comment, and dashboard) are unchecked and disabled by default. Extra options to toggle the Quick Edit buttons, Media buttons, Screen Options and Help links. Toggle to Restrict Comment Editing to Editor+ roles. SuperAdmin comments can only be edited by a SuperAdmin.
Extra options to toggle the Quick Edit buttons, Media buttons, Screen Options and Help links.

I use the plugin to simplify the various edit forms available to the entire network of sites. 

Added a toggle so only users with at least an Editor role can edit others comments. I also wanted SuperAdmin comments to be editable only by SuperAdmin.


== Installation ==

This section describes how to install the plugin and get it working.

1. Upload the plugin to your blog, Network Activate it
2. Set multisite "Meta Boxes" options at Network->Settings page

== Frequently Asked Questions ==

* Will this plugin also hide meta boxes added by plugins? No.
* Will this plugin disable media buttons? Yes, but you'll need additional means to disable uploads entirely.
* Can I have different meta boxes for different roles of users on different blogs? No, this plugin toggles meta boxes for all users and all blogs regardless of Cap/Role (SuperAdmin can override the limits of the plugin however).

== Screenshots ==

1. Meta Box Network->Settings: Enable Administration Meta Boxes

== Changelog ==
= 4.6 =
* WP 4.6 tests OK, cleanup php notices

== Upgrade Notice ==
= 4.6 =
* WP 4.6 tests OK, cleanup php notices