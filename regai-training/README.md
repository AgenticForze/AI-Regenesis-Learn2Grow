# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
npm install
```

**Note**: feel free to use the package manager of your choice.

## Local Development

```bash
npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment (GitHub Pages)

This project is configured for GitHub Pages hosting from the AgenticForze GitHub organization.

### Required GitHub setting

In the repository settings on GitHub:

1. Open Settings -> Pages
2. Set Source to "GitHub Actions"
3. Keep the repository branch as `master` for the deployment workflow

### Publish workflow

The repository includes a GitHub Actions workflow in `.github/workflows/deploy.yml` that builds the site and deploys it to GitHub Pages whenever changes are pushed to `master`.

### Local build

```bash
npm run build
```
