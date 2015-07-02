# Antispambot

A simple shortcode that hides your email address from spam robots in WordPress.

Antispambot translates each character of your email address into its HTML character entity. It looks and works normal to humans, but makes no sense to robots. Learn more at the [WordPress Codex](http://codex.wordpress.org/Protection_From_Harvesters).

[Download Antispambot](https://github.com/cferdinandi/antispambot/archive/master.zip)

**In This Documentation**

1. [Getting Started](#getting-started)
2. [How to Contribute](#how-to-contribute)
3. [License](#license)



## Getting Started

Getting started with Antispambot is as simple as installing a plugin:

1. Upload the `antispambot` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the Plugins menu in WordPress.
3. Use the `[email_antispambot]` shortcode in the WordPress editor.

```html
<a href="mailto:[email_antispambot encode='your@email.com']">[email_antispambot encode='your@email.com']</a>
```

And that's it, you're done. Nice work!



## How to Contribute

In lieu of a formal style guide, take care to maintain the existing coding style. Please apply fixes to both the development and production code. Don't forget to update the version number, and when applicable, the documentation.



## License

The code is available under the [MIT License](LICENSE.md).