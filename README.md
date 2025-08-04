# PrivacyPal Website

Landing page for PrivacyPal - AI Without Compromise

## GitHub Pages Setup

This site is configured for GitHub Pages hosting with custom domain:
- **Primary Domain**: https://privacypal.ai
- **Alternate Domain**: https://www.privacypal.ai

## Files

- `index.html` - Main landing page
- `pp-logo.png` - PrivacyPal logo
- `CNAME` - Custom domain configuration for GitHub Pages
- `robots.txt` - SEO configuration
- `404.html` - Custom 404 error page
- `.gitignore` - Git ignore patterns

## Local Development

To run locally, simply open `index.html` in a web browser or serve it with a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve .
```

## Deployment

This site automatically deploys to GitHub Pages when pushed to the main branch. The custom domain is configured via the `CNAME` file.

## Domain Configuration

The domain `privacypal.ai` should be configured with the following DNS settings:
- CNAME record pointing to your GitHub Pages URL
- GitHub Pages should be enabled in repository settings with custom domain set to `privacypal.ai`