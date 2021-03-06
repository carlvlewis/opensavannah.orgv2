Built with [Gatsby.js](https://www.gatsbyjs.org/docs/building-with-components/)



## How you can help

In the spirit of free software, everyone is encouraged to help improve this project.  Here are some ways you can contribute.

- Comment on or clarify [issues](link to issues)
- Report [bugs](link to bugs)
- Suggest new features
- Write or edit documentation
- Write code (no patch is too small)
  - Fix typos
  - Add comments
  - Clean up code
  - Add new features

**[Read more about contributing.](CONTRIBUTING.md)**

## Requirements

You will need the following things properly installed on your computer.

* **[Git](https://git-scm.com/)**
* **[Node.js](https://nodejs.org/)** (with NPM)
* **[gatsby-cli](https://www.npmjs.com/package/gatsby-cli)** (to run [Gatsby](https://www.gatsbyjs.org/) commands)
* **[Yarn](https://yarnpkg.com/)**

## Local development

- Clone this repo `git clone git@github.com:NYCPlanning/labs-planninglabs-home.git`
- Navigate to the project directory `cd labs-planninglabs-home`
- Run `yarn` to install dependencies
- `gatsby develop` — Gatsby will start a hot-reloading development environment accessible at `localhost:8000`. Edit the javascript pages in src/pages. Saved changes will live reload in the browser.
- `gatsby build` — Gatsby will perform an optimized production build for your site generating static HTML and per-route JavaScript code bundles.
- `gatsby serve` — Gatsby starts a local HTML server for testing your built site.

## Backend services

- **[Airtable](https://airtable.com/)** (used to manage project content)
- **[labs-ideas-api](https://github.com/NYCPlanning/labs-ideas/)** (pulls in projects from Airtable)

## Deployment

This project can be deployed on any static web server.

- Deploy via Dokku using `npm run deploy`

