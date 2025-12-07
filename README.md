# PocketLog Support Website

This repository hosts the support website for PocketLog - a personal relationship journal app for iOS.

## Website

Visit: **[pocketlog.github.io](https://pocketlog.github.io)**

## Pages

| Page | File | Description |
|------|------|-------------|
| **Home** | `index.md` | App overview, features, FAQ, and support contact |
| **Privacy Policy** | `privacy.md` | Privacy policy for App Store compliance |
| **Terms of Use** | `terms.md` | Terms and conditions |

## Structure

```
pocketlog.github.io/
├── _config.yml          # Jekyll configuration
├── _includes/
│   └── head-custom.html # Custom head elements (CSS, meta tags)
├── assets/
│   ├── app-icon.png     # App icon for branding
│   └── custom.css       # Custom styles
├── index.md             # Home page
├── privacy.md           # Privacy policy
├── terms.md             # Terms of use
└── README.md            # This file
```

## Features

- **Responsive Design**: Works on desktop and mobile
- **Collapsible FAQ**: Easy-to-navigate FAQ sections
- **Visual Cards**: Feature highlights with icons
- **Branded Colors**: Consistent with app design
- **SEO Optimized**: Open Graph and Twitter Card meta tags

## Setup

This site uses GitHub Pages with the Jekyll Cayman theme. To enable:

1. Go to repository Settings
2. Navigate to Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Save

The site will be available at `https://pocketlog.github.io`

## Local Development

```bash
# Install Jekyll
gem install bundler jekyll

# Run locally
bundle exec jekyll serve

# View at http://localhost:4000
```

## Contact

For app support: [pocketlog.app@gmail.com](mailto:pocketlog.app@gmail.com)
