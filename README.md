# Figma Plugin Template with React & Tailwind CSS.

This template builds off of the original [Figma Plugin React Template](https://github.com/nirsky/figma-plugin-react-template) but has been modified to include  support for Tailwind CSS.

## Why
Tailwind CSS is great, especially when it comes to prototyping applications. Many of times, Figma plugins are simple one-off solutions built to solve for a limitation of Figma. Because of this, Tailwind is naturally a great choice for building Figma plugins.

## Quickstart
* Run `npm install` to install dependencies.
* Run `npm build:watch` to start webpack in watch mode.
* Open `Figma` -> `Plugins` -> `Development` -> `New Plugin...` and choose `manifest.json` file from this repo.

## Toolings
This repo is using:
* React + Webpack
* TypeScript
* Tailwind CSS (PostCSS)
* Prettier precommit hook
