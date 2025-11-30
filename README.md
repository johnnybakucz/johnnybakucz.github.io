# Academic Personal Website

A Jekyll-based academic personal website inspired by [Aakaash Rao's site](https://aakaashrao.github.io/).

## Quick Start

### Local Development

1. Install Ruby and Bundler if not already installed
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the local server:
   ```bash
   bundle exec jekyll serve
   ```
4. Open `http://localhost:4000` in your browser

### Customization

1. Edit `_config.yml` to update your personal information:
   - Name, title, institution
   - Social links (GitHub, Google Scholar, etc.)
   - Location and contact info

2. Update content pages:
   - `index.md` - Your main page with research and publications
   - `cv.md` - Your curriculum vitae
   - `teaching.md` - Your teaching experience

3. Add your profile photo:
   - Place your photo at `assets/images/profile.jpg`

4. Add your CV PDF:
   - Place your CV at `assets/files/cv.pdf`

## Deploying to GitHub Pages

1. Push this repository to GitHub as `yourusername.github.io`
2. GitHub Pages will automatically build and deploy your site
3. Your site will be available at `https://yourusername.github.io`

## Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # Page layouts
├── _includes/           # Reusable components
├── assets/
│   ├── css/            # Stylesheets
│   ├── images/         # Images (profile photo, etc.)
│   └── files/          # Files (CV PDF, etc.)
├── index.md            # Home page
├── cv.md               # CV page
└── teaching.md         # Teaching page
```

## Credits

Inspired by [AcademicPages](https://academicpages.github.io/), a fork of Minimal Mistakes Jekyll theme.
