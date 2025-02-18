# makebureau
# Make Bureau Website

Official repository for the Make Bureau website, deployed via Cloudflare Pages.

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/makebureau.git
cd makebureau
```

2. Set up Cloudflare integration:
   - Go to Cloudflare Pages dashboard
   - Create a new project
   - Connect to this GitHub repository
   - Configure the following settings:
     - Build command: (leave empty for static site)
     - Build output directory: /
     - Root directory: /

3. Configure GitHub Secrets:
   - Go to repository Settings > Secrets and variables > Actions
   - Add the following secrets:
     - `CLOUDFLARE_API_TOKEN`: Your Cloudflare API token
     - `CLOUDFLARE_ACCOUNT_ID`: Your Cloudflare account ID

## Development

This is a static website built with HTML, CSS (Tailwind), and minimal JavaScript. To make changes:

1. Modify the files locally
2. Test changes by opening index.html in a browser
3. Commit and push to main branch
4. GitHub Actions will automatically deploy to Cloudflare Pages

## File Structure

- `index.html`: Main landing page
- `robots.txt`: Search engine configuration
- `assets/`: Contains all static assets
  - `css/`: Stylesheets
  - `js/`: JavaScript files
  - `images/`: Image assets

## Contact

For any questions or issues, please contact hello@makebureau.com
