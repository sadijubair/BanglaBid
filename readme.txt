# Bangla Web Fonts

**Bangla Web Fonts** is a lightweight WordPress plugin that enables beautiful and consistent rendering of Bangla (Bengali) text across all devices and browsers. It automatically applies a Bangla web font (Kalpurush) to your website, ensuring textbook-style typography and improved readability.

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [FAQ](#faq)
- [Credits](#credits)
- [Changelog](#changelog)
- [License](#license)

---

## Features

- Embeds Bangla web fonts directly into your WordPress site.
- Automatically applies the Kalpurush font site-wide.
- Cross-browser and device-compatible.
- Minimal configuration needed.
- Clean and optimized for performance.
- Works with most WordPress themes.

---

## Installation

### Method 1: Install via WordPress Admin Panel

1. Navigate to **Plugins → Add New**
2. Search for `Bangla Web Fonts`
3. Click **Install Now**, then **Activate**
4. You're done!

### Method 2: Manual Installation

1. Download the latest release from [GitHub Releases](https://github.com/[your-repo-link]/releases)
2. Upload the `.zip` file via **Plugins → Add New → Upload Plugin**
3. Click **Install Now**, then **Activate**
4. You're all set!

---

## Usage

Once the plugin is activated, it attempts to automatically apply the **Kalpurush** font site-wide.

If the font is not applied automatically, you can manually force it by adding this line to your theme's CSS:

```css
body {
  font-family: 'Kalpurush', Nunito, sans-serif !important;
}

This will override default fonts and apply the Bangla font as intended.


---

FAQ

Q: How does this plugin work?

It loads the Kalpurush Bangla font and applies it to your site’s body content using WordPress hooks.

Q: Can I use a different Bangla font?

At the moment, only Kalpurush is bundled. However, you can modify the plugin or use custom CSS to load other web-safe Bangla fonts.

Q: Is it compatible with all themes?

Yes, it works with most modern themes. In case of conflicts, use the manual CSS method described above.


---

Credits

Developer: Mohammad Sadi Jubair
Email: sadibhaai@gmail.com
Website: www.mohammadsadi.com
Facebook: facebook.com/mohammadsadijubair


---

Changelog

v1.0.0

Initial release

Kalpurush font embedding

Auto-apply to WordPress body text



---

License

This plugin is open-source software licensed under the GNU General Public License v2 or later.


---

> Empower your Bangla content with elegant typography — across every screen and every platform.



