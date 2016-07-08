=== OPCache Scripts ===
Contributors: nikdow
Donate link: http://www.cbdweb.net/donate
Tags: cache, dashboard, monitor, OPcache, scripts, memory, optimisation, php, server, stat, stats, status, zend
Requires at least: 3.0.1
Tested up to: 4.5.3
Stable tag: 0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Use this plugin to display detailed information about your server’s OPCache, including memory utilisation, and a list of all scripts cached.

== Description ==

Use this plugin to display detailed information about your server’s OPCache, including memory utilisation, list of all scripts cached and a useful memory utilisation visualisation based on the file system tree.

This plugin is based on https://github.com/rlerdorf/opcache-status which is for general PHP use, we have turned it into a WordPress plugin for ease of installation. Apart from some rearrangement of scripts to suit WP load conventions, the code is to date unaltered. WordPress capability ‘activate_plugins’ is required to see it in the admin menu and to run it.

After you install and activate this plugin, look in the admin Tools menu for OPCache.

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files to the `/wp-content/plugins/opcache-scripts` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Tools->OPCache screen to see details of your server's OPCache

== Frequently Asked Questions ==

= Is this plugin free =

Yes

== Screenshots ==

1. Status and visualisation of memory utilisation
1. List of scripts cached
1. Showing scripts loaded by file system structure, with visualisation of memory utilisation
1. OPCache configuration settings

== Changelog ==

= 0.2.1 =
* Improve screenshots

== Upgrade Notice ==

= 0.2.1 =
* Improve screenshots, no need to upgrade from 0.2
