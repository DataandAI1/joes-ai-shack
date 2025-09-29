# Deployment Guide

## GitHub Pages Deployment

Deploy Joe's AI Shack to GitHub Pages in just a few steps:

### Method 1: GitHub Pages (Recommended)

1. Go to your repository settings: https://github.com/DataandAI1/joes-ai-shack/settings/pages

2. Under "Source", select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`

3. Click **Save**

4. Wait 1-2 minutes for deployment

5. Your site will be live at:
   ```
   https://dataandai1.github.io/joes-ai-shack/
   ```

### Method 2: Netlify

1. Go to [netlify.com](https://netlify.com)
2. Click "Add new site" → "Import an existing project"
3. Connect your GitHub account
4. Select the `joes-ai-shack` repository
5. Deploy settings:
   - **Build command**: (leave empty)
   - **Publish directory**: `./`
6. Click "Deploy site"

### Method 3: Vercel

1. Go to [vercel.com](https://vercel.com)
2. Click "Add New" → "Project"
3. Import your GitHub repository
4. Deploy with default settings

### Method 4: Local Development

To run locally:

```bash
# Clone the repository
git clone https://github.com/DataandAI1/joes-ai-shack.git

# Navigate to directory
cd joes-ai-shack

# Open in browser
open index.html

# Or use a local server (optional)
python -m http.server 8000
# Then visit http://localhost:8000
```

## Custom Domain (Optional)

To use a custom domain with GitHub Pages:

1. Add a `CNAME` file to the repository with your domain
2. Configure DNS with your domain provider:
   - Add an `A` record pointing to GitHub's IPs
   - Or add a `CNAME` record pointing to `dataandai1.github.io`
3. Update repository settings with custom domain

## Notes

- The site is pure HTML/CSS/JS with no build process required
- No dependencies or frameworks needed
- Works on any static hosting platform
- Mobile responsive and ready to deploy

---

**Live Site**: Once deployed to GitHub Pages, your site will be available at:
https://dataandai1.github.io/joes-ai-shack/
