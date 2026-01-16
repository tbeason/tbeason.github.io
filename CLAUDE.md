# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal website for Tyler Beason, deployed to GitHub Pages at tbeason.com. Simple static HTML/CSS site with no build step.

## Site Structure

- `index.html` - Single-page site with all content (About, Insights, Code, Teaching)
- `style.css` - Minimal custom styles
- `assets/` - Images, PDFs, favicons
- `CNAME` - Custom domain configuration

## Development

Open `index.html` directly in a browser to preview. No build step required.

## Deployment

Push to `dev` branch triggers GitHub Actions (`.github/workflows/deploy.yml`) which copies files to `master` branch for GitHub Pages.

- **`dev`** - Development branch (push changes here)
- **`master`** - Auto-deployed, do not edit directly
