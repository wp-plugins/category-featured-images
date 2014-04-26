=== Category Featured Images ===
Contributors: blocknot.es
Tags: images,categories,posts,Post
Donate link: http://www.blocknot.es/home/me/
Requires at least: 3.0
Tested up to: 3.9
Stable tag: trunk
License: GPL3
License URI: http://www.gnu.org/licenses/gpl-3.0.txt

Set a featured image for all the posts of a category.

== Description ==

This plugin allows to set a featured image for each category.
Posts without a featured image set will show the category's featured image instead.
Featured images usually are placed by the theme in the single post page, in the latest posts page, etc.
But can also be shown using the shortcode [cfi_featured_image] or the PHP function cfi_featured_image()

Shortcode/PHP function optional arguments:
- 'size': 'thumbnail', 'medium', 'large', 'full'
- 'class': class of the image tag
- 'alt': alternative text of the image tag
- 'title': title of the image tag

Shortcode example: [cfi_featured_image size="large" title="This is a test..." class="my-image" alt="My image"]

Function example: cfi_featured_image( array( 'size' => 'large', 'title' => 'This is a test...', 'class' => 'my-image', 'alt' => 'My image' ) );

== Installation ==

1. Install and activate the plugin
2. Go in Posts \\ Categories
3. Edit a category
4. Set the category featured image

== Screenshots ==
1. Edit category page

== Changelog ==

= 1.0.6 =
* Added PHP function and shortcode: cfi_featured_image
