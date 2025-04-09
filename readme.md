# Banglabid – Bangla Web Fonts for WordPress

**Banglabid** is a lightweight WordPress plugin that brings elegant and consistent Bangla (Bengali) typography to your website. With minimal setup, it automatically applies a beautiful Bangla web font (Kalpurush) that looks just like it does in textbooks — across all browsers and devices.

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [FAQ](#faq)
- [Contributing](#contributing)
- [Credits](#credits)
- [Changelog](#changelog)
- [License](#license)

---

## Features

- One-click activation — no setup required.
- Automatically loads and applies the **Kalpurush** Bangla web font.
- Ensures consistent and readable Bangla text across all devices.
- Works seamlessly with most WordPress themes.
- Clean and minimal code for fast performance.

---

## Installation

### Option 1: From WordPress Dashboard

1. Go to **Plugins > Add New**
2. Search for **Banglabid**
3. Click **Install Now** → **Activate**

### Option 2: Manual Installation

1. Download the latest version from the [Releases](https://github.com/your-username/banglabid/releases)
2. Upload the plugin folder to `/wp-content/plugins/`
3. Activate the plugin from **Plugins > Installed Plugins**

---

## Usage

After activation, **Banglabid** automatically applies the Kalpurush font to your site. If it doesn't appear to work (due to theme conflicts), add the following CSS to your theme's customizer or `style.css`:

```css
body {
  font-family: 'Kalpurush', 'Nunito', sans-serif !important;
}

You can also apply it to specific elements:

h1, h2, h3, p {
  font-family: 'Kalpurush', sans-serif !important;
}


---

FAQ

Why isn't the font showing up?

Some themes override fonts with higher specificity. Use the manual CSS override (with !important) to enforce it.

Can I use a different Bangla font?

Currently, Kalpurush is the only bundled font. Future versions may support multiple font options.

Will this slow down my website?

Not at all! The plugin uses a single web font hosted locally, ensuring fast load times without relying on external CDNs.


---

Contributing

Pull requests, issues, and feature suggestions are welcome!

1. Fork the repository


2. Create your branch: git checkout -b feature/your-feature


3. Commit your changes: git commit -m 'Add some feature'


4. Push to the branch: git push origin feature/your-feature


5. Submit a pull request




---

Credits

Author: Mohammad Sadi Jubair
Email: sadibhaai@gmail.com
Website: www.mohammadsadi.com
Facebook: facebook.com/mohammadsadijubair


---

Changelog

v1.0.0

Initial release of Banglabid

Kalpurush font integration

Auto-apply functionality for Bangla font



---

License

This plugin is licensed under the GNU General Public License v2 or later.


---

> Banglabid – Because your Bangla content deserves to look its best.



---

Let me know if you’d like help fixing the plugin code itself or adding support for font switching, Gutenberg integration, or Elementor compatibility.

.
