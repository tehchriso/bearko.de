# bearko.de

A placeholder landing page for bearko.de, built with Jekyll for GitHub Pages.

## Features

- Dark theme with deep, earthy color palette (greens, browns, eggplant)
- Bright lime green and white accents
- Fully static - no dependencies required
- Mobile responsive
- Minimal and elegant design

## Local Development

To run locally:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## DNS Configuration

Once ready, point your bearko.de DNS records to GitHub Pages:

1. Go to your domain registrar (Infomaniak)
2. Add the following DNS records:
   - For `bearko.de`: Point to GitHub Pages IP addresses
   - For `www.bearko.de`: CNAME to `tehchriso.github.io`
3. Update the `baseurl` in `_config.yml` if using a subdirectory

See [GitHub Pages DNS documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) for detailed instructions.

## Future Updates

This is a single-page placeholder. Content can be expanded by:
- Adding more pages in the root directory
- Using Jekyll layouts and includes
- Adding CSS assets in an `assets/` directory
