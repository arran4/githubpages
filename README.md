# githubpages

This repository is a simple example of a Hugo site that can be deployed with GitHub Pages. Treat it as a template to build your own site. The live example is available at <https://arran4.github.io/githubpages/>.


## Requirements

- [Hugo](https://gohugo.io/) static site generator must be installed. On Ubuntu
  you can install it with `apt-get install hugo` or download a binary from the
  [Hugo releases page](https://github.com/gohugoio/hugo/releases).

## Running the site locally

Run the following command in the repository root to start a development server:

```bash
hugo server
```

The site will be served at <http://localhost:1313> by default.

## Repository structure

- `content/` – Markdown files that make up the site content.
- `themes/` – Custom themes used by the site.
- `archetypes/` – Templates for new content.
- `config.toml` – Main configuration file.

Feel free to fork this repository as a starting template for your own Hugo + GitHub Pages site.
