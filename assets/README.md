# Assets Folder

This folder contains images and media files for Joe's AI Shack website.

## Files

- **hero.png** - Main hero image showing Joe and the beach shack
  - Used on homepage and about page
  - Used as social media preview image (Open Graph)
  - Used as favicon/browser icon
  - Recommended dimensions: 1200x600px or similar 2:1 ratio
- Additional images, logos, or media assets can be placed here

## Usage

Images in this folder are referenced in the HTML files using:

```html
<img src="assets/hero.png" alt="Description">
```

Or via GitHub raw URLs for external/social media use:
```html
<meta property="og:image" content="https://raw.githubusercontent.com/DataandAI1/joes-ai-shack/main/assets/hero.png">
```

## Social Media Preview

The `hero.png` image is configured as the preview image for:
- Open Graph (Facebook, LinkedIn)
- Twitter Cards
- GitHub repository social preview

## Favicon

The `hero.png` is also used as the browser favicon/icon on all pages.

## Image Guidelines

- Use web-optimized formats (PNG for hero image, JPEG for photos)
- Keep file sizes reasonable for web performance (< 500KB recommended)
- For social media previews, recommended size is 1200x630px
- PNG format preferred for images with transparency or sharp graphics
