# Antispambot

A simple shortcode that hides your email address from spam robots in WordPress.

Antispambot translates each character of your email address into its HTML character entity. It looks and works normal to humans, but makes no sense to robots. Learn more at the [WordPress Codex](http://codex.wordpress.org/Protection_From_Harvesters).

**In This Documentation**

1. [Getting Started](#getting-started)
2. [Options & Settings](#options-and-settings)
3. [Browser Compatibility](#browser-compatibility)
4. [License](#license)
5. [Changelog](#changelog)
6. [Older Docs](#older-docs)



## Getting Started

Getting started with Antispambot is as simple as installing a plugin:

1. Upload the `antispambot` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the Plugins menu in WordPress.
3. Use the `[email_antispambot]` shortcode in the WordPress editor.

```html
<a href="mailto:[email_antispambot email='your@email.com']">[email_antispambot email='your@email.com']</a>
```

And that's it, you're done. Nice work!



## License

Antispambot is licensed under the [MIT License](http://gomakethings.com/mit/).



## Changelog

* v1.1 - November 6, 2013
	* Renamed plugin `WP Email Antispambot` to avoid conflicts with another plugin.
* v1.0 - October 16, 2013
	* Initial release.