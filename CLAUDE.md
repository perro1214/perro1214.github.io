# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Type
This is a GitHub Pages repository (perro1214.github.io) hosting a professional portfolio website for Hayato Harada.

## Architecture Overview
This is a static portfolio website built with vanilla HTML, CSS, and JavaScript:

- **index.html**: Single-page application with sections for hero, about, skills, projects, and contact
- **style.css**: CSS with custom properties for consistent theming, responsive design, and animations
- **script.js**: Interactive features including mobile navigation, smooth scrolling, and scroll-based animations

## Design System
The site uses a cohesive blue color palette defined in CSS custom properties:
- Primary blue (#4981cf), secondary blue (#89aad3), light purple (#c8cbf2), pale blue (#cadaec)
- Typography: Inter font family with weight variations (300-700)
- Responsive design with mobile-first approach

## Content Structure
- Hero section with name, title, and call-to-action buttons
- About section highlighting educational background (TMU, 42 Tokyo) and JOI achievement
- Skills section categorized by programming languages, technologies, and specialties
- Projects section featuring 4 main projects: FdF, Tetris AI, minitalk, and ft_printf
- Contact section with email, GitHub, and AtCoder links

## Development Workflow
- Direct file editing - no build process required
- Changes are automatically deployed via GitHub Pages on push to main branch
- Site accessible at https://perro1214.github.io

## Project Links
All project repository links use the GitHub username "perro1214":
- FdF: https://github.com/perro1214/42_FdF
- Tetris AI: https://github.com/perro1214/tetris_AI
- minitalk: https://github.com/perro1214/42_minitalk
- ft_printf: https://github.com/perro1214/42_printf

## Key Features
- Responsive mobile navigation with hamburger menu
- Smooth scrolling between sections
- CSS animations and hover effects
- Intersection Observer for scroll-triggered animations
- Performance-optimized with throttled scroll events