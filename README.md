# Tools documentation

A lightweight documentation site for practical tooling patterns, reference guides, and copyable sample projects. This repository powers the `tools.envai.tr` site and is designed to help teams quickly set up small but production-minded utilities.

## What this project includes

- A simple static documentation site built with GitHub Pages and Jekyll
- A quickstart guide for getting a project running in minutes
- Example patterns for CLI tools, webhook relays, and dashboard reports
- A clean structure for adding future guides and reusable examples

## Repository structure

- `index.md` — homepage for the docs site
- `docs/` — guide pages such as Quickstart, FAQ, and sample projects
- `_config.yml` — site metadata and Jekyll configuration
- `_layouts/` — page templates
- `assets/` — static assets and CSS/JS files
- `CNAME` — custom domain configuration for the deployed site

## Project purpose

This project acts as a reference library for practical software tools. It focuses on realistic patterns that can be adapted for real projects without requiring a large framework or heavy setup.

The docs cover common tasks such as:

- starting a small CLI workflow
- validating and forwarding inbound webhooks
- generating lightweight HTML or JSON reporting dashboards
- documenting internal tooling for reuse across projects

## Local development

This repository is configured for GitHub Pages, so the simplest workflow is to commit changes and let Pages publish the site.

If you want to preview the site locally with Jekyll:

```bash
bundle install
bundle exec jekyll serve
```

Then open the URL shown in the terminal, usually `http://localhost:4000`.

## Contributing

To add new content:

1. Create or edit files under `docs/`
2. Link new pages from `index.md` or the relevant guide
3. Keep examples concise, clear, and practical
4. Validate the site build before publishing changes

## License

This project is licensed under the terms of the included `LICENSE` file.

