# CLAUDE.md - Project Context

## Project Overview

The site is a heartfelt digital love letter featuring photos and text organized into thematic sections.

**Type:** Jekyll static site (GitHub Pages)
**Language:** French (Français)
**Purpose:** Anniversary celebration website
**Deployment:** GitHub Pages (via CNAME configuration)

## Image Assets

All images are stored in `assets/img/` and include:
- Family photos with daughter Marguerite
- Photos with Boris (appears to be a pet)

## Styling Notes

- Custom CSS flex layouts for responsive image galleries
- Multiple font families for varied typography
- Custom footer styling
- Responsive design considerations

## Development Workflow

**All development runs through Docker.** Do not run Jekyll or bundle commands directly on the host.

1. **Local Development (Docker):**
   ```bash
   docker compose up -d
   ```
   This starts the Jekyll dev server with live reload at http://localhost:4000.
   The `compose.yaml` handles `bundle install` and `jekyll serve` automatically.

## Git Information
- **Main Branch:** master (for PRs)

## Important Considerations

- **Language:** All content is in French; maintain language consistency
- **Personal Nature:** This is a deeply personal project; be respectful and maintain the emotional tone
- **Image Optimization:** Consider image sizes for web performance
- **Mobile Responsiveness:** Ensure layouts work well on various screen sizes
- **Privacy:** This contains personal photos and information

## Tips
Everytime you get confused, or need to do some heavy tool usage, add a tip here to speed up future development.