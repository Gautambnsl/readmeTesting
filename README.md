Certainly! Here's the modified README file with "edexa.js" instead of "matic.js":

```markdown
# Edexa SDK

[![GitHub version](https://img.shields.io/github/v/release/USERNAME/REPOSITORY)](https://github.com/USERNAME/REPOSITORY/releases)
[![Build Status](https://github.com/USERNAME/REPOSITORY/actions/workflows/build.yml/badge.svg)](https://github.com/USERNAME/REPOSITORY/actions/workflows/build.yml)
[![npm version](https://img.shields.io/npm/v/edexa-sdk)](https://www.npmjs.com/package/edexa-sdk)
[![GitHub TEST](https://img.shields.io/github/workflow/status/USERNAME/REPOSITORY/TEST?label=GitHub%20TEST)](https://github.com/USERNAME/REPOSITORY/actions/workflows/test.yml)

This repository contains the `edexa.js` client library. `edexa.js` makes it easy for developers, who may not be deeply familiar with smart contract development, to interact with the various components of Edexa Network.

This library will help developers move assets from the Ethereum chain to the Edexa chain and withdraw from Edexa to Ethereum using fraud proofs.

## Docs

[https://wiki.edexa.technology/docs/tools/edexa-js/get-started](https://wiki.edexa.technology/docs/tools/edexa-js/get-started)

## Support

Our Discord is the best way to reach us ✨.

## Contributors

You are very welcome to contribute, please see contributing guidelines - [Contribute](CONTRIBUTING.md).

Thank you to all the people who already contributed to `edexa.js`!

[![Made with contributors-img](https://img.shields.io/badge/Made%20with-contributors--img-green)](https://contributors-img.web.app/)

## Development

### Setup

```bash
npm ci
```

### How to debug

Write your code inside the file `test/debug.js` and run the following code:

```bash
npm run debug
```

The above command will build the source code & install the built version into the `test` folder, which will be used by `debug.js`.

### Lint

To check lint errors:

```bash
npm run lint
```

To fix most common lint errors (Note that it might not fix all errors, some need manual intervention):

```bash
npm run lint:fix
```

### Build code

```bash
npm run build
```

### Run test

```bash
npm run test
```

### Generate distribution files

```bash
npm run deploy
```

### NPM publish

Before running the publish script, make sure you have updated the version properly.

Note that the `prepublishOnly` script will be automatically called while publishing. It will check lint, clean `dist/lib` folders, and build fresh distribution files before executing `npm publish`.

```bash
npm publish
```

## License

MIT
```

Replace `USERNAME` and `REPOSITORY` with your actual GitHub username and repository name. Additionally, create a `CONTRIBUTING.md` file for contributing guidelines and update the relevant link in the README.
