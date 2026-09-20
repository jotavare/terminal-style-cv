## ABOUT

A one-page "about me" site styled like a Linux terminal, built with
[Jekyll](https://jekyllrb.com/) on top of the
[jekyll-theme-console](https://github.com/b2a3e8/jekyll-theme-console) theme
and served with GitHub Pages.

Live at <https://jotavare.github.io/terminal-style-cv/>.

## HOW TO USE

#### 1º - Clone the repository

```bash
git clone https://github.com/jotavare/terminal-style-cv.git
cd terminal-style-cv
```

#### 2º - Install the dependencies

```bash
bundle install
```

#### 3º - Serve the site

```bash
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## THEMES

The theme ships three colour schemes, switched with the `style` key in
`_config.yml`:

- `dark` (default)
- `light`
- `hacker`

## DEPLOYMENT

Pushes to `main` trigger `.github/workflows/jekyll.yml`, which builds the site
with Jekyll and publishes `_site` to GitHub Pages.
