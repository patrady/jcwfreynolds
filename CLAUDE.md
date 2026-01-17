# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Reynolds Oil Company, a fictional Texas oil company. The site is a single-page marketing website with no build process or dependencies.

## Project Structure

- `index.html` - Single-page HTML with all content (navigation, hero, about, history timeline, services, contact form, footer)
- `styles.css` - All styling including responsive breakpoints at 768px and 480px

## Development

To view the site, open `index.html` in a browser or use any local server:

```bash
python3 -m http.server 8000
# or
npx serve .
```

## Design System

- **Colors**: Dark navy (#1a1a2e) and gold (#d4a84b) palette
- **Typography**: Playfair Display (headings), Source Sans Pro (body) via Google Fonts
- **Layout**: CSS Grid for main layouts, Flexbox for navigation and smaller components
