# Featured Image for Pressboks CPTs

* Contributors: @colomet @danzhik @huguespages @lukastonhajzer
* Donate link: https://opencollective.com/mylanguageskills
* Tags: multisite, pressbooks, images, media, thumbnail, feature-image, wordpress plugin
* Requires at least: 3.0.1
* Tested up to: 5.2.2
* Requires PHP: 5.6.0
* Stable tag: 0.8
* License: GNU 3.0
* License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

A WordPress plugin that extends PressBooks with new image sizes and Feature images.

## Community / Support

You can contact us via our [chat](https://gitter.im/books4languages/)  and talk to us.                                  

## Description

Featured Image for Pressbooks CPTs extends basic PressBooks plugin functionality by supporting thumbnails for all kinds of posts and also provides an ability to set thumbnail with external link,
with addition of visual control of attached thumbnail and support of PressBooks book sizes in front-end and in text area.

By activating, Pressbooks CPTs will create additional image sizes with the same Width as the Webbook Width (in theme options **508** for Narrow; **688** for Standard; **832** for Wide). The feature image will use the same image size as the Webbook width (Narrow, Standard or Wide).

Feature image for PressBooks automatically set the image Title, Alt-Text, Caption & Description upon upload to any image, not just Feature Images.

If extensions-for-pressbooks plugin is activate, a new settings page will be available on Appeareance where advance settins will be available.

* Feature images deactivation to mobiles.
* Import images from parent book.

Import images from parent books means: If the book is created by cloning a book, the post of the child books can import the images from the parent book. Imported feature images can be overwritten.

## Installation

1. Clone or download this repository to your host ```/wp-content/plugins/```.
1. Activate the plugin through the 'Plugins' screen in WordPress.

## Frequently Asked Questions
* [General Documentation](doc/documentation-general.md)
* [Technical Documentation](doc/documentation-technical.md)
* [The Folder Structure](doc/folder-structure.md)

## Requirements

Plugin works with:

 * ![PHP](https://img.shields.io/badge/PHP-7.X-blue.svg)
 * [![WordPress](https://img.shields.io/badge/Wordpress-4.9.5-green.svg)](https://codex.wordpress.org/Version_4.9.5)
 * [![Pressbooks](https://img.shields.io/badge/Pressbooks-V%205.3.0-red.svg)](https://github.com/pressbooks/pressbooks/releases/tag/5.3.0)
 * [Extensions for Pressbooks plugin](https://github.com/my-language-skills/extensions-for-pressbooks) (for advanced functionality settings)

## Disclaimers

The Featured Image for Pressbooks plugin is supplied "as is" and all use is at your own risk.

## Screenshots
You can see all of the screenshots of the theme [here](https://github.com/my-language-skills/pressbooks-featured-image/blob/developer/screenshots/screenshots.md).

## Roadmap

## Changelog
### 0.8
* **ADDITIONS**
  * nonce, authorization checks

* **ENCHANCEMENTS**
  * Functions renaming (prefixes)
  * Minor text changes and visual enhancements

* **MODIFICATIONS**
  * Change querry checking from post_name to post_type (more stable)

* **REMOVED**
  * Empty section callback function

### 0.7
* Major rework (upgrade) of plugin functionality

* **ADDITIONS**
  * Featured images are now able to be imported from Source to all of its clones from EFP Customization settings.
  * Bottom field of featured image metabox in post-edit page changed to display information about availability of source images. More information in documentation-technical.

* **REMOVED**
  * Functionalities related to adding featured images by URL.

* **ENCHANCEMENTS**
  * documentation
  * files renamed, some functions relocated
  * Remove displaying of disabled RUN button in clone books

* **BUGFIX**
  * Variables check.

* **List of Files revised**
  * fifp-admin-settings.php
  * featured-iamges-for-pressbooks.php

### 0.6
* **ADDITIONS**
  * Featured images section in EFP Customization settings page.
  * Functionality to disable displaying featured images on mobile devices for the book.

* **ENCHANCEMENTS**
  * documentation

* **List of Files revised**
  * featured-image-for-pressbooks.php
  * added fifp-admin-settings.php

### 0.5
* **REMOVED**
    *  Autoloader

### 0.4
* **ENCHANCEMENTS**
  * New sizes in attachment display settings. By default is selected the size of the blog.

* **ADDITIONS**
  * Automatically set the image Title, Alt-Text, Caption & Description upon upload

* **List of Files revised**
       * featured-image-for-pressbooks.php

### 0.3
* **ENCHANCEMENTS**
    * Set good size

### 0.2
* **ADDITIONS**
    * Activate the post-thumbnails in theme

* **ENCHANCEMENTS**
    * New file name
    * Change autoloader parameters

### 0.1
* **ADDITIONS**
    * Use a media stored image as a featured image
    * Use an external image as a featured image via URL
    * Set appropriate featured image size according to Pressbooks books sizes
    * Monitor featured images from posts administration area


## Upgrade Notice

## Credits
Here's a link to [Alecaddd](http://www.alecaddd.com/) [WordPressPlugin101](https://github.com/Alecaddd/WordPressPlugin101) on [YouTube](https://www.youtube.com/playlist?list=PLriKzYyLb28kR_CPMz8uierDWC2y3znI2).

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software").
