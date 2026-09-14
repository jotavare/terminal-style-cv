<p align="center">
	<img src="https://img.shields.io/badge/status-finished-success?color=%2312bab9&style=flat-square" />
	<img src="https://img.shields.io/github/license/jotavare/terminal-style-cv?color=%2312bab9&style=flat-square" />
	<img src="https://img.shields.io/github/languages/top/jotavare/terminal-style-cv?color=%2312bab9&style=flat-square" />
	<img src="https://img.shields.io/github/last-commit/jotavare/terminal-style-cv?color=%2312bab9&style=flat-square" />
	<a href='https://www.linkedin.com/in/jotavare' target="_blank"><img alt='Linkedin' src='https://img.shields.io/badge/LinkedIn-blue?style=flat-square'/></a>
</p>

<p align="center">
	<a href="#about">About</a> •
	<a href="#how-to-use">How to use</a> •
	<a href="#themes">Themes</a> •
	<a href="#deployment">Deployment</a> •
	<a href="#contributing">Contributing</a> •
	<a href="#license">License</a>
</p>

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

## CONTRIBUTING

This repository is finished and not open to changes.

## LICENSE

This project is available under the MIT License. For further details, please refer to the [LICENSE](https://github.com/jotavare/terminal-style-cv/blob/main/LICENSE) file. The theme itself is MIT-licensed by [b2a3e8](https://github.com/b2a3e8/jekyll-theme-console).
