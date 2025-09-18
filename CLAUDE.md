# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based GitHub Pages site serving as James Williams' professional CV/resume website. The site is deployed at cv.perpetualvector.com.

## Architecture

- **Static Site Generator**: Jekyll with the `jekyll-theme-architect` theme
- **Content**: Single-page CV stored in README.md
- **Deployment**: GitHub Pages with custom domain (cv.perpetualvector.com)
- **Theme**: Jekyll Architect theme configured in `_config.yml`

## Key Files

- `README.md` - Contains the complete CV content in Markdown format
- `_config.yml` - Jekyll configuration specifying the theme
- `CNAME` - Custom domain configuration for GitHub Pages
- `perpetual-vector-logo.png` - Logo image (currently untracked)

## Common Commands

This is a static Jekyll site with no build process required. GitHub Pages automatically builds and deploys the site when changes are pushed to the main branch.

To preview locally (if Jekyll is installed):
```bash
bundle exec jekyll serve
```

## Development Notes

- The site uses GitHub Pages' built-in Jekyll processing
- No custom plugins or complex build steps
- Content changes only require editing README.md
- Theme changes require modifying `_config.yml`
- The site automatically rebuilds on push to main branch

## Domain Configuration

The site is configured to serve from cv.perpetualvector.com via the CNAME file. Any changes to domain configuration should be made in this file.