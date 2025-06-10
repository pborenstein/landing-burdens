# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static landing page for Gravitique, a luxury technology brand focused on gravity-based solutions. The site is built with vanilla HTML/CSS and features a mid-century modern design aesthetic.

## Architecture

- **Single-page application**: All content is contained in `index.html`
- **Static CSS**: Styling is managed through `styles.css` with CSS custom properties for theming
- **No build process**: Direct HTML/CSS files that can be opened in a browser

## Design System

The site uses a cohesive design system built around CSS custom properties:

- **Typography**: Space Grotesk (primary/headings) and Inter (secondary/body text) from Google Fonts
- **Color palette**: Mid-century modern colors defined in `:root` variables
  - Primary: `#2C5F2D` (deep green)
  - Secondary: `#E85A4F` (warm orange)
  - Accent: `#D4A574` (gold)
- **Layout**: CSS Grid and Flexbox for responsive sections
- **Animations**: Subtle CSS animations for the gravity orb visual element

## Key Sections

- **Hero**: Full-height section with animated gravity orb visual
- **Features**: Three-column grid showcasing technology features
- **About**: Two-column layout with stats sidebar
- **CTA**: Call-to-action section for lead generation
- **Footer**: Brand and navigation links

## Development

- Preview: Open `index.html` directly in any modern web browser
- No build tools or package managers required
- Mobile-responsive design with breakpoint at 768px

## Content Guidelines

The brand positioning focuses on luxury/exclusivity ("for the one percent") with gravitational technology as the core offering. Content should maintain this premium, scientific aesthetic.