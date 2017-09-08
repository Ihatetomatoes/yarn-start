# Getting started with YARN

This repo contains the most commonly used commands for <code>yarn</code>.

Why to use [Yarn](https://yarnpkg.com/en/) instead of [NPM](https://www.npmjs.com/)?

* it is fast
* it is reliable
* it is secure

## 1. Init Yarn

    yarn init

## 2. Install NPM package eg. Webpack

    //latest stable version
    yarn add webpack

    //specific version
    yarn add react@0.13.0

## 3. Show NPM package info

    yarn info webpack

## 4. Show all versions of NPM package

    yarn info webpack versions

## 5. Show all commands and flags

    yarn help

## 6. Install all dependecies listed in package.json

    yarn install

## 7. List all packages and their dependencies

    yarn list --depth=0

## 8. List outdated packages

    yarn outdated

## 9. Upgrade outdated packages

    // upgrade all packages to the latest version
    yarn upgrade --latest
    
    // upgrade specific package
    yarn upgrade <package>

## 10. Remove package

    yarn remove <package>

## 11. yarn.lock file

All <code>yarn.lock</code> files should be checked into source control.

This allows Yarn to install the same exact dependency tree across all machines, whether it be your coworker’s laptop or a CI server.