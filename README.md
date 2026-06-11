# AriaPay WordPress Theme

Custom WordPress theme built for [AriaPay](https://www.ariapay.io/) — a Persian-language fintech and services website with dedicated layouts for news, training, services, and customer support pages.

## Features

- RTL-ready layout with Persian typography (Peyda, Clash Display)
- Custom page templates: home, services, news, trainings, blog, FAQ, contact, about, and more
- Mega menu and separate mobile navigation
- Advanced Custom Fields (ACF) options integration
- Custom search logic with AJAX support
- Tailored comment system and template parts
- Service pages with plans, purchase guides, FAQs, and related content blocks

## Requirements

- WordPress 6.0+
- PHP 7.4+
- [Advanced Custom Fields](https://www.advancedcustomfields.com/) (recommended)

## Installation

1. Download or clone this repository.
2. Upload the `ariapay` folder to `wp-content/themes/`.
3. In **Appearance → Themes**, activate **AriaPay**.
4. Configure menus under **Appearance → Menus** (Primary, Mobile, Footer menus).
5. Import or configure ACF field groups if your site uses theme options.

## Theme structure

```
ariapay/
├── assets/          # CSS, JS, fonts, images
├── inc/             # Theme setup, enqueue, hooks, helpers, ACF, search
├── template-parts/  # Reusable header, blog, services, and comment partials
├── page-*.php       # Custom page templates
├── single-*.php     # Single post templates (news, trainings, blog)
└── functions.php    # Loads theme includes
```

## Author

**Ayda Firouzi** — [@aydafirouzi](https://aydafirouzi.com/)

## License

Proprietary theme developed for AriaPay. Contact the author for reuse permissions.
