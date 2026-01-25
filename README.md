# Hugo GitHub Pages Template

This repository is a template for building a Hugo site deployed with GitHub Pages.

## Getting Started

1.  Click the **"Use this template"** button to create a new repository from this template.
2.  Clone your new repository to your local machine.
3.  Install [Hugo](https://gohugo.io/) (Extended version recommended).

## Configuration

Update `config.toml` with your site details:

-   `baseURL`: Set this to your GitHub Pages URL (e.g., `https://<username>.github.io/<repo>/`).
-   `title`: Your site title.
-   `params.author`: Your name.

## Running Locally

Run the following command to start a development server:

```bash
hugo server
```

The site will be available at <http://localhost:1313>.

## Deployment

This repository includes a GitHub Actions workflow (`.github/workflows/gh-pages.yml`) that automatically deploys your site to the `gh-pages` branch when you push to `main`.

Ensure you have GitHub Pages enabled in your repository settings:
-   Source: Deploy from a branch
-   Branch: `gh-pages` / `/ (root)`

## Repository Structure

-   `content/`: Markdown files for your site content.
-   `themes/basic/`: The default theme. You can modify this or install a new theme.
-   `archetypes/`: Templates for new content.
-   `config.toml`: Main configuration file.
