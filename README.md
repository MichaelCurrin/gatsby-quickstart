# Gatsby Quickstart

> Starter template for a static site built with Gatsby

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/gatsby-quickstart)](https://github.com/MichaelCurrin/gatsby-quickstart/releases/?include_prereleases&sort=semver)
[![License: 0BSD](https://img.shields.io/badge/License-0BSD-blue)](#license)

<div align="center">
    <a href="https://www.gatsbyjs.com">
        <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
    </a>
</div>

## Preview

<div align="center">
    <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" />
</div>

<div align="center">

[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge&logo=github)](https://github.com/MichaelCurrin/gatsby-quickstart/generate)

</div>

## Resources

- [Gatsby homepage](https://www.gatsbyjs.com/)
- [Gatsby docs](https://www.gatsbyjs.com/docs/)
- [Gatsby quickstart guide](https://www.gatsbyjs.com/docs/quick-start/)

## Setup

```sh
$ cd REPO
$ npm install
```

## Commands

### Development

Start the dev server.

```sh
$ npm start
```

Then open in the browser:

- [localhost:8000](http://localhost:8000)
- [localhost:8000/\_\_\_graphql](http://localhost:8000/___graphql)

Format with Prettier:

```sh
$ npm run format
```

If you want to use GitHub Actions to deploy to GitHub Pages, see this [workflow](https://github.com/MichaelCurrin/react-quickstart/blob/master/.github/workflows/main.yml) for a React app.

### Production

Build for production:

```sh
$ npm run build
```

View the result in the `public` directory.

After the build, you can serve it.

```sh
$ npm run serve
```

Open in the browser:

- http://localhost:9000/

Clean - delete `.cache.` and `public`:

```sh
$ npm run clean
```

## Create new project

Starter repo: https://github.com/gatsbyjs/gatsby-starter-hello-world

Install Node.js then run this command.

```sh
$ npx gatsby-cli new gatsby-site https://github.com/gatsbyjs/gatsby-starter-hello-world
$ cd gatsby-site
$ npm start
```

## License

Released under [0BSD](/LICENSE).
