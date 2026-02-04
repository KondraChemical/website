# Kondra Chemical Website

A professional Jekyll website for Kondra Chemical, a chemistry hardware and laboratory equipment supplier.

## Features

- Clean, modern responsive design
- Mobile-friendly navigation
- Home page with hero section, features, and product highlights
- Products page showcasing equipment categories
- About page with company information
- Contact page with form and business details

## Quick Start

### Prerequisites

- Ruby 2.7+
- Bundler (`gem install bundler`)

### Installation

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

### Build for Production

```bash
bundle exec jekyll build
```

The static site will be generated in the `_site` directory.

## Project Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Main layout template
├── assets/
│   └── css/
│       └── style.css    # All styles
├── index.html           # Home page
├── products.html        # Products catalog
├── about.html           # About page
├── contact.html         # Contact page
├── Gemfile              # Ruby dependencies
└── README.md
```

## Customization

### Colors

Edit the CSS variables in `assets/css/style.css`:

```css
:root {
  --primary: #1a5f7a;
  --secondary: #57c5b6;
  --accent: #159895;
  /* ... */
}
```

### Content

- Update company information in `_config.yml`
- Edit page content directly in the HTML files
- Replace lorem ipsum text with actual company content

## Deployment

This site can be deployed to:

- **GitHub Pages**: Push to a `gh-pages` branch or enable Pages in repo settings
- **Netlify**: Connect your repo and deploy automatically
- **Any static host**: Upload the `_site` directory after building

## License

All rights reserved.
