=== Redirect Unattached Images ===
Contributors: fatmedia, ozzyr, cipherdevgroup
Donate link: https://cipherdevelopment.com
Tags: images, galleries, 301, redirect, SEO, search engine optimization
Requires at least: 4.1.2
Tested up to: 5.4.2
Stable tag: 0.1.2
License: GPL-2.0+

Redirect attachment pages for all unattached images to the current site's home page.

== Description ==

The default behavior in WordPress is to generate attachment pages for all of the images in your media library. While this can sometimes be useful, it can also cause problems.

When you upload an image to your media library without inserting it into a post or page, it becomes an unattached image. By default, these images generate attachment pages with no pretty permalink structure. This isn't very useful for anyone, including search engines.

This plugin takes all of these unattached images and safely redirects them using a 301 redirect to your site's home page. If you're using WordPress multisite, it redirects to the current site's home page. There are no options or settings, just install, activate, and enjoy better SEO and less useless pages on your website!

== Installation ==

The easiest way to install this plugin is to download directly form the WordPress admin panel and active the plugin. Alternatively, you can download it and install it manually by doing the following:

1. Upload the `redirect-unattached-images` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Sit back and relax. You're done!

== Frequently Asked Questions ==

None yet!

== Changelog ==

= 0.1.2 =
Change of ownership.

= 0.1.1 =
Made a minor improvement to the way attachments are checked before being redirected.

= 0.1.0 =
Initial release.
