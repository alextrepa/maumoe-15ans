# CLAUDE.md - Project Context

## Project Overview

This is a personal Jekyll-based static website celebrating 15 years of relationship between Alex and Maude. The site is a heartfelt digital love letter featuring photos and text organized into thematic sections.

**Project Name:** maumoe-15ans
**Type:** Jekyll static site (GitHub Pages)
**Language:** French (Français)
**Purpose:** Anniversary celebration website
**Deployment:** GitHub Pages (via CNAME configuration)

## Project Structure

```
maumoe-15ans/
├── _config.yaml          # Jekyll configuration
├── _layouts/             # Custom HTML layouts
│   └── default.html      # Main layout template
├── assets/
│   ├── css/
│   │   └── style.scss    # Custom styling
│   └── img/              # Photo gallery (15+ images)
├── index.md              # Main content page
├── CNAME                 # Custom domain configuration
└── README.md             # Project description
```

## Technology Stack

- **Static Site Generator:** Jekyll
- **Theme:** jekyll-theme-tactile (customized)
- **Fonts:**
  - Mali (body text)
  - Mrs Saint Delafield (decorative)
  - Sour Gummy (supplementary)
- **Hosting:** GitHub Pages
- **Styling:** SCSS/CSS

## Content Structure

The [index.md](fleet-file://st80f0uhooqrrbomq9u1/Users/a.trepanier/Repos/Personnal/Maude/maumoe-15ans/index.md?type=file&root=%252F) file contains six main sections:

1. **Ma chère Maude, mon tendre amour** - Introduction celebrating 15 years together
2. **Ma chère Maude, ma compagne de voyage** - Travel memories and adventures
3. **Ma chère Maude, ma voisine de divan** - Shared entertainment and cozy moments
4. **Ma chère Maude, ma partenaire culinaire** - Food experiences and culinary adventures
5. **Ma chère Maude, ma motivatrice** - Personal growth and support
6. **Ma chère Maude, ma chère Marguerite, ma famille** - Family with their daughter Marguerite

## Key Files

### [_config.yaml](fleet-file://st80f0uhooqrrbomq9u1/Users/a.trepanier/Repos/Personnal/Maude/maumoe-15ans/_config.yaml?type=file&root=%252F)
- Theme: jekyll-theme-tactile
- Title: "Maude et Alex"
- Description: "Déjà 15 ans de vie commune et ça ne fait que commencer!"

### [_layouts/default.html](fleet-file://st80f0uhooqrrbomq9u1/Users/a.trepanier/Repos/Personnal/Maude/maumoe-15ans/_layouts/default.html?type=file&root=%252F)
- Custom header with dynamic title and description
- Main content section
- Custom footer with publication date (November 17, 2024)

### [index.md](fleet-file://st80f0uhooqrrbomq9u1/Users/a.trepanier/Repos/Personnal/Maude/maumoe-15ans/index.md?type=file&root=%252F)
- Main content with embedded images
- Uses flexbox layouts for multi-column image displays
- Markdown with inline HTML for layout control

## Image Assets

All images are stored in `assets/img/` and include:
- Couple photos from various locations (Greece, Cape May, aquarium, etc.)
- Family photos with daughter Marguerite
- Photos with Boris (appears to be a pet)
- Travel and food-related memories

**Image formats:** JPG and PNG

## Styling Notes

- Custom CSS flex layouts for responsive image galleries
- Multiple font families for varied typography
- Custom footer styling
- Responsive design considerations

## Development Workflow

This is a Jekyll site, so typical workflow includes:

1. **Local Development:**
   ```bash
   jekyll serve
   # or
   bundle exec jekyll serve
   ```

2. **Building:**
   ```bash
   jekyll build
   ```

3. **Deployment:** Automatic via GitHub Pages on push to master branch

## Git Information

- **Current Branch:** master
- **Main Branch:** master (for PRs)
- **Recent Notable Commits:**
  - e0530ad - fix: footer width
  - cc0084b - fix: switch jpg to png
  - 337d0d8 - feat: adds boris
  - cf93110 - feat: adds motivation pictures

## Important Considerations

- **Language:** All content is in French; maintain language consistency
- **Personal Nature:** This is a deeply personal project; be respectful and maintain the emotional tone
- **Image Optimization:** Consider image sizes for web performance
- **Mobile Responsiveness:** Ensure layouts work well on various screen sizes
- **Privacy:** This contains personal photos and information

## Future Enhancement Ideas

- Add image lazy loading for performance
- Consider adding a photo gallery with lightbox functionality
- Add smooth scrolling between sections
- Consider progressive image loading
- Add meta tags for social media sharing (Open Graph, Twitter Cards)

## Contact

**Author:** Alex Trépanier
**Published:** November 17, 2024

---

*This file was created to provide context for Claude Code interactions with this project.*
