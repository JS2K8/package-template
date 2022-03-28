# package-template

A template for publishing a React + TypeScript package to npm

## How to use

Edit the `package.json` along with every other required file to match your project.

To compile your code once, run

- `npm run build`.

To compile your code once and refresh on file change, run

- `npm run start`.

Compile your package by running

- `npm run build`

Update the package version accordingly by using

- [`npm version [patch | minor | major]`](https://docs.npmjs.com/about-semantic-versioning)

or automatically increment the version with "npm version patch".

Then publish your package by running

- "npm adduser --registry \<our registry domain\>"
- "npm publish --registry \<our registry domain\>"
