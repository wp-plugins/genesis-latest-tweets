=== Genesis Latest Tweets ===
Contributors: studiopress, nick_thegeek, nathanrice
Tags: adopt-me, genesis, genesiswp, twitter, tweets
Requires at least: 3.5.0
Tested up to: 3.5.1
Stable tag: 1.2.3

The official plugin from the StudioPress team.

== Description ==

__Note: This plugin is no longer actively developed nor maintained!__

__Note: This plugin is available for adoption.__

Genesis Latest Tweets will add a new widget allowing you to show your latest tweets in any widget area. This plugin requires the Genesis theme framework which is available from StudioPress.com.

== Installation ==

1. Upload `genesis-latest-tweets` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Why do I have to configure API keys? =

Twitter changed their system early 2013 and dropped support for the old system in mid 2013. Now it is impossible to show the tweets on your site without using authorization from Twitter. There are two ways we can do that, but because we use open PHP it is just too easy for someone to get our keys and use them to ruin everyone's experience, so the simple Oauth approach doesn't work. Instead we are using the method which requires each user to setup their own authorization keys. Then if someone tries to abuse things only that person loses.

== Changelog ==

= 1.2.3 =
* Officially marking this plugin as unsupported and putting it up for addoption

= 1.2.2 =
* Fixed error that could result in an undefined function warning in certain circumstances

= 1.2.1 =
* Fixed a few typos

= 1.2.0 =
* Fixed the hash tag link builder
* Changed some strings for clarity

= 1.1.0 =
* Updated to Twitter API to 1.1

= 0.2.0 =
* Initial Version

