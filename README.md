# Academic website scaffold

This repository was scaffolded with a minimal Jekyll-based site. Replace the placeholder content with your own information.

What I added

- _config.yml — site configuration
- _layouts/default.html — simple page layout and navigation
- index.md, about.md, cv.md, publications.md, projects.md, teaching.md, contact.md — content pages (markdown)
- publications.bib — placeholder for BibTeX
- assets/css/styles.css — basic styles

How to publish

- For a user site (username.github.io) GitHub Pages will serve the site automatically from the repository root. After these files are pushed, the site should be available at https://davidecastellani.github.io within a minute or two.

Preview locally (optional)

1. Install Ruby and Bundler. On macOS use Homebrew: `brew install ruby`
2. Install jekyll: `gem install bundler jekyll`
3. Run: `bundle exec jekyll serve --watch` from the repository root and open http://localhost:4000

If you don't want to install Ruby, you can edit files directly on GitHub and view changes when Pages rebuilds.


