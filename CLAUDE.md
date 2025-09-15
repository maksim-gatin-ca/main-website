# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal website for Maksim Gatin, a young developer. The site is a single-page application built with vanilla HTML, CSS, and JavaScript that showcases his coding journey and projects with a fun, casual tone.

## Architecture

- **Single HTML file**: `index.html` contains all the HTML structure, embedded CSS styles, and JavaScript functionality
- **Static assets**: Images are stored in the `images/` directory
- **Self-contained**: No external dependencies, build tools, or package managers - everything runs directly in the browser

## Key Components

- **Hero section**: Profile photo (images/maksim-photo.jpeg), name, subtitle with casual tone, and animated coding icons
- **About section**: Personal introduction with fun, encouraging language - avoid formal "programmer" terminology
- **Games section**: Grid layout showcasing completed games and "coming soon" placeholder cards
- **Interactive features**: Animated sparkles effect, hover animations, and floating icon animations

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
- Uses CSS Grid for games section layout (responsive auto-fit grid)
- Gradient backgrounds and modern card-based design
- Responsive design with mobile breakpoints
- CSS animations for interactive elements (sparkles, floating icons, hover effects)

## Content Guidelines

- **Tone**: Keep language casual, fun, and age-appropriate - avoid pressure-inducing terms like "Future Programmer"
- **Age references**: Avoid mentioning specific age - use abstract terms like "young developer" or "code enthusiast"
- **Game cards**: Each game should have both "Play Game" and "View Code" buttons linking to live demo and GitHub repo
- **Coming soon cards**: Use encouraging, excited language about future projects

## External Links

- Games link to binaryforce.ca for live demos
- GitHub repositories link to maksim-gatin-ca organization
- All external links open in new tabs (_blank target)