# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal website for Maksim Gatin, an 11-year-old developer. The site is a single-page application built with vanilla HTML, CSS, and JavaScript that showcases his coding journey and projects.

## Architecture

- **Single HTML file**: `index.html` contains all the HTML structure, embedded CSS styles, and JavaScript functionality
- **Static assets**: Images are stored in the `images/` directory
- **Self-contained**: No external dependencies, build tools, or package managers - everything runs directly in the browser

## Key Components

- **Hero section**: Profile photo placeholder, name, and animated coding icons
- **About section**: Personal introduction and coding journey
- **Games section**: Showcases developed games with links to external repositories
- **Interactive features**: Animated sparkles effect and hover animations

## Development Workflow

Since this is a static HTML website with no build process:

1. **Local development**: Open `index.html` directly in a browser or use a simple HTTP server
2. **Testing**: Manual testing in browser - no automated test suite
3. **Deployment**: Direct file hosting (the site links to external games on GitHub Pages)

## File Structure

```
.
├── index.html          # Main website file (HTML, CSS, JS all embedded)
├── images/             # Static image assets
│   └── maksim-photo.jpeg
└── README.md           # Basic project description
```

## Styling Approach

- All CSS is embedded in the `<style>` tag within `index.html`
- Uses CSS Grid/Flexbox for layout
- Gradient backgrounds and modern card-based design
- Responsive design with mobile breakpoints
- CSS animations for interactive elements

## External Links

The website links to external game projects hosted on GitHub Pages. When working with games section, verify that linked URLs are accessible and functional.