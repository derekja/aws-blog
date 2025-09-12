# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static blog website documenting AWS explorations for university research. The project consists of:

- `index.html` - Main blog page with a single article about AWS exploration in university settings
- `styles.css` - Complete styling for the blog with AWS-inspired design theme
- `README.md` - Basic project description
- Image assets (PNG/MP4 files) - Visual content for blog posts

## Architecture

This is a simple static website with no build system or dependencies:

- **Frontend**: Pure HTML5 with CSS3 styling
- **Styling**: Custom CSS using Inter font family with AWS color scheme (#232f3e primary, #ff9900 accent)
- **Layout**: Responsive design with mobile-first approach
- **Content**: Academic blog format with author bios and structured article layout

## Key Features

- Responsive design that works on desktop and mobile
- AWS-inspired color scheme and typography
- Author bio cards with placeholder avatars
- Tag system for content categorization
- Clean academic blog layout optimized for readability

## Development Workflow

Since this is a static site with no build process:

1. Edit HTML directly in `index.html`
2. Modify styles in `styles.css`
3. Test by opening `index.html` in a browser
4. No compilation or build steps required

## Content Structure

The blog follows this content hierarchy:
- Site header with title and subtitle
- Article metadata with category tags
- Main article content with structured headings
- Author bio section with cards for each contributor
- as blog entries are added, newer entries will appear at the top, older entries at the bottom. Some entries may be authored by a single person and others have multiple authors
- each entry should have a separate date, title, and author byline

## Authors

The blog is authored by Reed Huang, Derek Jacoby, and Yvonne Coady from university research teams exploring AWS technologies in academic environments.