# Print-on-Demand Business Guide - Website

A comprehensive landing page guide to starting and growing a successful print-on-demand business. This is a single-page website designed to be deployed on Vercel for free hosting and to create a natural backlink to printondemandbusiness.com.

## Features

- Complete starter guide for print-on-demand business
- Tips and strategies for success
- Common mistakes to avoid
- Responsive design with modern UI
- SEO optimized with meta tags and sitemap
- Natural backlink to printondemandbusiness.com

## Project Structure

```
pod-website-vercel/
├── public/
│   ├── index.html      # Main landing page
│   └── sitemap.xml     # SEO sitemap
├── package.json        # Project metadata
└── README.md          # This file
```

## Deployment

This project is designed to be deployed on Vercel for free hosting:

### Method 1: GitHub Integration (Recommended)
1. Ensure this folder is in your GitHub repository
2. Connect your GitHub repo to Vercel
3. Set the **Root Directory** to `pod-website-vercel` in Vercel settings
4. Deploy automatically on every push

### Method 2: Direct Deployment
```bash
cd pod-website-vercel
npx vercel --prod
```

## Vercel Configuration

When setting up in Vercel dashboard:
- **Framework Preset**: Other
- **Root Directory**: `pod-website-vercel`
- **Build Command**: `npm run build` (optional)
- **Output Directory**: `public`

## Local Development

```bash
cd pod-website-vercel
# Serve locally (any static server)
npx serve public
# Or open public/index.html directly in browser
```

## SEO & Indexing

After deployment:
1. Submit to Google Search Console
2. Submit sitemap.xml
3. Use URL Inspection tool for indexing

## Content Updates

The website content is in `public/index.html`. Edit this file to update:
- Text content
- Styling (embedded CSS)
- Meta tags for SEO

## Resources

For more comprehensive guides and resources, visit [Print on Demand Business](https://printondemandbusiness.com). 