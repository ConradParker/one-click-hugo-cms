# SunSeaSangria

Hugo site with Paige theme and Decap CMS integration, deployed on Netlify.

## Deployment

This site is built on Netlify which provides Hugo Extended with Dart Sass (required by Paige theme).

Deploy to Netlify by connecting your GitHub repository. The `netlify.toml` handles all build configuration.

## Local Development

Local development requires Hugo Extended with Dart Sass installed. Without it, you can still edit content and push to Netlify for preview.

To install Hugo Extended locally:
1. Download from https://github.com/gohugoio/hugo/releases (choose "extended" version)
2. Install Dart Sass: https://sass-lang.com/install

Then run:
```bash
hugo server -D
```

## Content Management

Content is managed through Decap CMS at `/admin/` route. The CMS allows you to:
- Create and edit blog posts
- Manage pages
- Upload and organize media files

## Theme

This site uses the [Paige Hugo theme](https://github.com/willfaught/paige), which provides:
- Responsive design
- Dark/light mode support
- Clean, modern aesthetics
- Excellent typography