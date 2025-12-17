# draxus.org

Personal website for Manuel Martín Salvador (draxus) - AI Researcher & Software Engineer.

## Tech Stack

- **Static Site Generator:** Hugo
- **Hosting:** GitHub Pages
- **Languages:** Spanish (default), English

## Development

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.100.0+)

### Local Development

```bash
hugo server -D
```

Site will be available at `http://localhost:1313/`

### Build

```bash
hugo --minify
```

Output will be in the `public/` directory.

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions when pushing to the `main` branch.

## Structure

```
├── content/          # Markdown content (ES/EN)
├── themes/draxus/    # Custom theme
│   ├── layouts/      # HTML templates
│   └── static/css/   # Stylesheets
├── static/           # Static assets
└── hugo.toml         # Site configuration
```

## License

Content © Manuel Martín Salvador. Code under MIT License.
