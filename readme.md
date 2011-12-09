# FitVids.js for WordPress

A simple WordPress plugin that wraps up the [FitVids.js](http://fitvidsjs.com/) jQuery plugin by [Chris Coyier](http://chriscoyier.net/) & [Paravel](http://paravelinc.com/).

## Description

Embedded videos resize responsively and at the correct aspect ratio. 

Demos:

- [FitVids.js](http://fitvidsjs.com/)
- [Ryan Clark Merrill – Goodbye, Steve.](http://ryanmerrill.net/post/9355364787)

(Try resizing your browser window)

## How it works

The plugin simply enqueues FitVids.js and hooks onto the `.hentry` selector which is used on posts and pages in WordPress when the `post_class` funtion is used. Which all themes should have.

## Instructions

1. Upload to your WordPress plugin directory, usually `wp-content/plugins` and activate from the plugin menu.

2. Enjoy responsive video embeds!

## License

This plugin is available for public use and modification under  [WTFPL](http://sam.zoy.org/wtfpl/).

## Credits

[Chris Coyier](http://css-tricks.com), [Dave Rupert](http://daverupert.com) and [Thierry Koblentz](http://www.alistapart.com/articles/creating-intrinsic-ratios-for-video/).