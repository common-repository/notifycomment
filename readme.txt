=== WP NotifyComment ===
Contributors: phd38
Donate link: http://www.photos-dauphine.com/wp-notify-comment
Tags: comment, notification, moderator, mail
Requires at least: 2.7
Tested up to: 3.4.2
Stable tag: 1.0.0


== Description ==

**WP NotifyComment** is a very simple single pluggable function plugin with no widget interface. A mail is sent to the moderator when a new comment is posted, to alert him that moderation is awaited. This function was originally working on the first WordPress versions and then has behaved erratically after a change in code (malformed header).


== Installation ==

To install the **WP NotifyComment** plugin just follow this simple 5-step recipe :

1. Download the plugin and expand it to an empty directory of your local disk drive.
2. Copy the local *wp-notify-comment* folder created by the unzipper onto your server plugins folder (*wp-content/plugins/*).
3. Login into the WordPress administration area and click on the *Plugins* left menu. Expand the *Installed* view.
4. Locate the *NotifyComment* plugin and click on the *Activate* link. Check that the plugin is actually listed as activated.
5. You are done, check now a comment is sent if you post a comment (not being logged as administrator).
  
More information on this widget utilization can be found [there](http://www.photos-dauphine.com/wp-notify-comment "WP NotifyComment Home").


== Frequently Asked Questions ==

= What is this plugin fixing in the original pluggable function ? =

The mail header formatted by the standard *wp_notify_postauthor* function is empty instead of containing the required fields. This plugin fills the fields correctly.

= Is there any configuration required in the admin panel ? =

Nope. Nothing other than activating the plugin itself.


== Changelog ==

= 1.0.0 =
- First release. NotifyComment initial implementation.
