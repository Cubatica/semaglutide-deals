# GLP-1 Semaglutide Deals Landing Page

## Overview
Landing page for GLP-1 weight loss medication providers comparison and reviews. Features a responsive design with mobile-optimized navigation and provider comparison tables.

## Recent Updates
- **Mobile Navigation Fix**: Fixed burger menu visibility issue - now only shows on mobile devices (screens < 768px)
- **Menu Animation**: Smooth slide-in animation from left side on mobile
- **Responsive Design**: Fully responsive layout with optimized mobile experience

## Deployment
This site is configured for deployment on Cloudflare Pages via GitHub.

### Quick Deploy to Cloudflare Pages
1. Push this repository to GitHub
2. Connect your GitHub repository to Cloudflare Pages
3. Set build settings:
   - Build command: (leave empty - no build required)
   - Build output directory: `/glp1s`
4. Deploy

## Configuration

### Updating Affiliate/Tracking Links
All affiliate links currently point to `https://elixa.pages.dev/`

To update all links at once:
1. Open `index.html`
2. Search and replace: `https://elixa.pages.dev/`
3. Replace with your actual tracking URL

Each link includes data attributes for tracking:
- `data-provider`: Identifies the provider (medvi, futurehealth, etc.)
- `data-position`: Tracks link position (card-main, comparison-table, etc.)
- `data-original`: Preserves original tracking parameters for reference

### Directory Structure
```
glp1s.semaglutide-deals.com/
├── index.html          # Main landing page
├── css/               # Stylesheets and fonts
│   ├── style.css
│   └── *.woff2        # Font files
├── images/            # All images
│   ├── logos
│   ├── banners
│   └── icons
└── README.md
```

## Local Development
To test locally:
```bash
cd glp1s.semaglutide-deals.com
python3 -m http.server 8080
```
Then visit: http://localhost:8080

## Features
- Mobile responsive design
- Clean, professional layout
- Provider comparison table
- FAQ section
- Tracking-ready with data attributes
- SEO optimized meta tags

## Notes
- All tracking/analytics code has been removed
- Links are placeholder and need to be updated with actual affiliate URLs
- Images are locally hosted for better performance
- Fonts are preloaded for faster rendering

## License
Private - All rights reserved