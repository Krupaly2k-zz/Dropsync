=== WP Sync for Dropbox ===
Contributors: krupaly2k
Donate link: http://www.scopeship.com
Tags: dropbox-wp sync
Requires at least: 3.0.1
Tested up to: 3.4
Stable tag: 4.3
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin will sync dropbox files with wp. It will show dropbox files from users account to admin.

== Description ==

This plugin will be helpful for admin to display all their dropbox files to wp-admin. Admin can upload new files from admin to dropbox, delete files, create new folder in dropbox from wp-admin. Upload dropbox friles to wp media folder from wp-admin and use those files in their posts.

A few notes about the sections above:

*   "Contributors" is a comma separated list of wp.org/wp-plugins.org usernames
+*   "Tags" is a comma separated list of tags that apply to the plugin
*   "Requires at least" is the lowest version that the plugin will work on
*   "Tested up to" is the highest version that you've *successfully used to test the plugin*. Note that it might work on
higher versions... this is just the highest one you've verified.
*   Stable tag should indicate the Subversion "tag" of the latest stable version, or "trunk," if you use `/trunk/` for
stable.

    Note that the `readme.txt` of the stable tag is the one that is considered the defining one for the plugin, so
if the `/trunk/readme.txt` file says that the stable tag is `4.3`, then it is `/tags/4.3/readme.txt` that'll be used
for displaying information about the plugin.  In this situation, the only thing considered from the trunk `readme.txt`
is the stable tag pointer.  Thus, if you develop in trunk, you can update the trunk `readme.txt` to reflect changes in
your in-development version, without having that information incorrectly disclosed about the current stable version
that lacks those changes -- as long as the trunk's `readme.txt` points to the correct stable tag.

    If no stable tag is provided, it is assumed that trunk is stable, but you should specify "trunk" if that's where
you put the stable version, in order to eliminate any doubt.

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload `dropsync.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. In Admin >> Dropsync >> Settings, you can add your dropbox token and directory path
4. In Admin >> Dropsync, admin can see files listing from directory they have mentioned in settings. These files are displaying from their dropbox account.
5. Admin can upload and delete files from wp admin which will reflect on their dropbox account. Admin can upload files from dropbox to wp media folder from wp admin >> dropsync. The same media files admin can use in wp posts.  

== Frequently Asked Questions ==

= Will it display dropbox files and folders to wp-admin? =

Yes.

= Can admin upload new files to their dropbox account from wp-admin? =

Yes.

= Can admin rename files from wp-admin? =

No.

= Can admin use dropbox files in posts? =

Yes. There is an option to upload files to wp media folder.


== Screenshots ==

1. Screenshot1.png
2. Screenshot2.png

== Changelog ==

= 1.0 =
* Intial version.

== Upgrade Notice ==

= 1.0 =
N/A


== A brief Markdown Example ==

Ordered list:

1. Display dropbox files to wp-admin
2. Admin can create new folder, upload files, delete files
3. Admin can upload files to wp media folder which will be used in posts

