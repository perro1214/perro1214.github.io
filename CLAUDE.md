# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Type
This is a GitHub Pages repository (perro1214.github.io) for hosting a static website.

## Common Commands
Since this is a new repository, the specific build/development commands will depend on the framework chosen:

### For Jekyll (GitHub Pages default)
- `bundle exec jekyll serve` - Run local development server
- `bundle exec jekyll build` - Build the site
- `bundle install` - Install dependencies

### For general static sites
- Local development server depends on chosen framework
- GitHub Pages will automatically build and deploy on push to main branch

## Architecture Notes
- This repository will serve as the source for a GitHub Pages site
- The site will be accessible at https://perro1214.github.io
- Files in the root directory or `docs/` folder (if configured) will be served
- GitHub Pages supports Jekyll by default, but can also serve plain HTML/CSS/JS

## Deployment
- Automatic deployment via GitHub Pages on push to main branch
- No manual deployment commands needed - GitHub handles this automatically