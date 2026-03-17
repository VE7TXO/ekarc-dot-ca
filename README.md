# East Kootenay Amateur Radio Club Website

Jekyll-based static website for the East Kootenay Amateur Radio Club (EKARC).

## Quick Start for GitHub Pages

### Option 1: Use as-is (Recommended)

1. Create a new repository on GitHub
2. Upload all files from this directory to the repository
3. Go to Settings > Pages
4. Select the `main` branch as the source
5. Your site will be published at `https://yourusername.github.io/repository-name/`

### Option 2: Local Development

If you want to develop locally:

1. Install Ruby (if not already installed)
2. Install Jekyll:
   ```bash
   gem install jekyll bundler
   ```
3. Install dependencies:
   ```bash
   bundle install
   ```
4. Run the local server:
   ```bash
   bundle exec jekyll serve
   ```
5. View at `http://localhost:4000`

## Adding New Pages

Create a new `.md` file with this frontmatter:

```yaml
---
layout: default
title: "Your Page Title"
---
```

## File Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page layouts
├── assets/css/          # Custom styles
├── images/              # Site images
├── documents/           # PDF documents
├── minutes-meeting/     # Meeting minutes (automatically included)
└── *.md                 # Content pages
```

## Customization

- Edit `_config.yml` to change site title, description, and navigation
- Edit `assets/css/style.css` to modify colors and styles
- Images should be placed in the `images/` folder

## Notes

- The site uses the Bitter font (similar to the original)
- Navigation is defined in `_config.yml`
- All `.md` files in the root directory become pages automatically
- Minutes files are in the `minutes-meeting/` folder
