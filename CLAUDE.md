# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static HTML website for "달성군 자원봉사센터" (Dalseong-gun Volunteer Center) featuring a non-contact volunteer activity portal. The site showcases various volunteer opportunities that can be participated in remotely.

## Architecture

- **Single HTML file**: `src/index.html` - Contains the complete website with embedded CSS and JavaScript
- **Static site**: No build process or dependencies required - can be opened directly in a browser
- **Responsive design**: CSS includes media queries for mobile and tablet responsiveness
- **Korean language**: All content is in Korean, targeting local volunteer activities

## Key Features

- Hero section with volunteer center branding
- Card-based layout showcasing 4 volunteer activity types:
  - Online education volunteering
  - Digital content creation
  - Online counseling services  
  - Data entry support
- Interactive card hover effects
- Responsive grid layout
- Click handlers that currently redirect to naver.com (placeholder functionality)

## Development

Since this is a static HTML file with no build process:

- **To view**: Open `src/index.html` directly in a web browser
- **To edit**: Modify the HTML file directly
- **No dependencies**: No package.json, npm, or build tools required
- **No tests**: No testing framework configured

## File Structure

```
/
├── src/
│   └── index.html    # Complete website (HTML + CSS + JS)
└── resource/         # Empty directory (possibly for future assets)
```

## Styling

- Uses modern CSS with gradients, flexbox, and grid
- Pink/coral color scheme (#ff6b8a primary)
- Embedded styles in `<style>` tag within HTML
- No external CSS frameworks or libraries

## JavaScript

- Minimal vanilla JavaScript for card interactions
- `redirectToActivity()` function for navigation (currently redirects to naver.com)
- Event listeners for card hover effects