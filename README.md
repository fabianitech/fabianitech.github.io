# DevPulse - GitHub Pages Jekyll Blog Template

A fully functional static blog template tailored for tech content creators, developers, and code bloggers.

## Features
- **Code Syntax Highlighting:** Powered by Rouge / Kramdown (Python, JS, TS, Bash, etc.).
- **Responsive Media Embeds:** Custom CSS for responsive YouTube videos and social media embeds (X/Twitter, Instagram).
- **Custom Styling:** Clean mobile-first design built on Minima with enhanced CSS for callouts, captions, and code blocks.
- **SEO & RSS:** Out-of-the-box support for `jekyll-feed` and `jekyll-seo-tag`.

## How to Deploy to GitHub Pages

1. **Create Repository:**
   - Create a new public repository on GitHub named `<your-username>.github.io`.

2. **Upload Template:**
   - Extract this project archive and upload/push all files to the `main` branch of your repository.

3. **Configure Settings:**
   - Open `_config.yml` and update `url` with `https://<your-username>.github.io`.
   - Update author details and blog title.

4. **Enable GitHub Pages:**
   - Go to **Settings > Pages** in your GitHub repository.
   - Under **Build and deployment**, set **Source** to `Deploy from a branch`.
   - Choose `main` branch and `/ (root)` folder, then click **Save**.

5. **Local Development (Optional):**
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
   Open `http://localhost:4000` in your browser.
