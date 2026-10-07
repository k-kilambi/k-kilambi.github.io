# Kumar Kilambi — Personal Portfolio

A static Jekyll site for `k-kilambi.github.io`. The actual website source lives
in this repository root and is designed for GitHub Pages to build from the
`main` branch and `/(root)`.

## Update the site

- Edit `index.md`, `about.md`, `work-experience.md`, or `contact.md` to change
  page content. Keep the YAML front matter at the top of each file.
- Update shared navigation and footer in `_includes/`.
- Update global colors, typography, and responsive styles in
  `assets/css/site.css`.
- Update the site URL or description in `_config.yml`.
- Keep `PLAN.md` internal; it is excluded from the generated pages.

## Preview locally

1. Install Ruby and RubyGems for your operating system.
2. Install Jekyll: `gem install jekyll`
3. From the repository root, run: `jekyll serve`
4. Open the local address printed by Jekyll, usually `http://127.0.0.1:4000`.

Jekyll builds the site from the root; no application framework or separate
build step is required on GitHub Pages.

## Check with Lighthouse

1. Run `jekyll serve` and open the local site in Chrome.
2. Open Chrome DevTools and select **Lighthouse**.
3. Select Performance, Accessibility, Best Practices, and SEO, then run the
   report. Review at both mobile and desktop sizes; the target is 90 or higher
   in each category.

## Publish with GitHub Pages

Use a repository named `k-kilambi.github.io`, then open its **Settings → Pages**
and set the source to **Deploy from a branch**, branch **main**, folder
**/(root)**. GitHub Pages will build the Jekyll site from these root-level
files.
