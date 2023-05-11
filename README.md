[![Quarto Publish](https://github.com/vanHeemstraSystems/create-an-npm-package/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/create-an-npm-package/actions/workflows/publish.yml)

create-an-npm-package
# Create a Node Package Manager (NPM) Package

Based on "Fully Automated npm publish using GitHub Actions and Semantic Release" at https://www.youtube.com/watch?v=QZdY4XYbqLI

Based on "Create and Publish packages to npm - React Component Library using tsdx" at https://www.youtube.com/watch?v=aVFasPXkyRE

Based on "n Intro To Using npm and ES6 Modules for Front End Development" at https://wesbos.com/javascript-modules

Can be read as "Automation Management" at https://app.gitbook.com/s/???/

Can be browsed as "Automation Management" at https://vanheemstrasystems.github.io/create-an-npm-package/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "Awesome Quarto" at https://github.com/mcanouil/awesome-quarto

Based on "Quarto Web" at https://github.com/quarto-dev/quarto-web and https://quarto.org/

Based on "Creating your personal website using Quarto" at https://ucsb-meds.github.io/creating-quarto-websites/

**WARNING**: In order for the automation to successfully push changes to the repository, make sure you have set the following at your repository's "Settings" > "Actions" > "General":

Workflow permissions

- [Checked]: Read and write permissions
- [Unchecked]: Read repository contents and packages permissions

If the option is disabled, you can enable that option under ORGANIZATION settings not REPO settings.

Organizations's "Settings" > "Actions" > "General":

Workflow permissions

- [Checked]: Read and write permissions
- [Unchecked]: Read repository contents and packages permissions

# Executive Summary

To commit changes after making file changes run the following command:

```
$ git add .
$ npx cz
```

This will trigger *commitizen (cz)* and you will be prompted to describe your change. 

Follow with ```git push```.

Our Github Actions workflow with automatically build a package from the source code and publish it to npm.

You can see the latest releases in the Github repository at https://github.com/vanHeemstraSystems/create-an-npm-package/releases

After a successful publish of the package to npm, you can view the package on npmjs.com by entering the following in the search on https://npmjs.com:

```
@vanheemstrasystems/create-an-npm-package
```

Or go directly to https://www.npmjs.com/package/@vanheemstrasystems/create-an-npm-package

To install the node module package use the following:

```
$ npm i @vanheemstrasystems/create-an-npm-package
```
