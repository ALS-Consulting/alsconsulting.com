# ALS Consulting - Coming Soon Page

A modern, beautiful "Coming Soon" page built with Jekyll and hosted on GitHub Pages.

## Features

- 🎨 Modern gradient design with animated particles
- 📱 Fully responsive layout
- ✨ Smooth animations and hover effects
- 📧 Email subscription form (ready for integration)
- 🔗 Social media links
- 📄 Policy pages with consistent styling
- ⚡ Optimized for GitHub Pages

## Local Development

To run this site locally:

1. Install Ruby and Bundler
2. Clone this repository
3. Run the following commands:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

## Customization

### Site Configuration

Edit `_config.yml` to customize:
- Site title and description
- Contact email
- Social media usernames
- SEO settings

### Content

- **Homepage**: Edit `index.html` to change the coming soon message
- **Policies**: Add new policy pages in Markdown format with the `policy` layout

### Styling

The main styles are in the layout files:
- `_layouts/coming-soon.html` - Main coming soon page
- `_layouts/policy.html` - Policy pages

## GitHub Pages Deployment

This site is configured to work automatically with GitHub Pages. Simply push to your repository and GitHub will build and deploy the site.

## Email Integration

The email form currently shows a simple alert. To integrate with a real email service:

1. Replace the form submission handler in `_layouts/coming-soon.html`
2. Consider using services like:
   - Netlify Forms
   - Formspree
   - ConvertKit
   - Mailchimp

## File Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/
│   ├── coming-soon.html  # Main page layout
│   └── policy.html       # Policy page layout
├── index.html            # Homepage
├── sms-policy.html
├── 404.html             # 404 error page
├── Gemfile              # Ruby dependencies
└── CNAME                # Custom domain configuration
```

## Support

For questions or support, contact: contact@alsconsulting.com
