# apps.opendata.scot

A Jekyll-based single page subsite directory for Open Data Scotland applications and resources, built with Bootstrap 5.

## Overview

This site provides a clean and easy-to-navigate landing page that links to the main Open Data Scotland resources:

- [opendata.scot](https://opendata.scot) - Main Open Data Scotland hub
- [govspend.opendata.scot](https://govspend.opendata.scot) - Government spending data
- [osm.dundee.opendata.scot](https://osm.dundee.opendata.scot) - OpenStreetMap Dundee resources
- [docs.opendata.scot](https://docs.opendata.scot) - Documentation and guides
- [communities.opendata.scot](https://communities.opendata.scot) - Community discussions and collaboration

## Development

### Prerequisites

- Ruby 3.2+
- Bundler gem

### Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   bundle install
   ```

### Building the Site

```bash
bundle exec jekyll build
```

### Development Server

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

### Deployment

The site is built using Jekyll and can be deployed to any static hosting service that supports Jekyll, including GitHub Pages.

## Structure

- `_config.yml` - Jekyll configuration
- `_layouts/default.html` - Main layout template with Bootstrap 5
- `index.html` - Homepage with navigation cards
- `assets/css/style.css` - Custom styles
- `Gemfile` - Ruby dependencies