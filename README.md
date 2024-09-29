# NextJS Primer for the FS Team

## Name

Chapter 3 - Optimizing Fonts and Images

* How to add custom fonts with `next/font`
* How to add images with `next/image`
* How fonts and images are optimized in NextJS.

### Why Optimize Fonts?

Unoptimized fonts can cause page performance issues such as:

* Cumulative Layer Shift. You may have seen this in the form of font `flashing`. Where the fallback image loads while the primary large or external font file loads.

#### How does NextJS mitigate this?

* NextJS automatically optimizes fonts in the application when leveraging `next/font`. It will download font files at build time and hosts them as static assets. The result being a reduction of network requests for fonts thus improving performance.

## Description

This repository will follow along with the NextJS Dashboard app [tutorial](https://nextjs.org/learn/dashboard-app) from the NextJS documentation. Each chapter of the tutorial is broken out as it's own branch. Incrementally building upon itself as the tutorial progresses.

## Installation

1. Run `nvm use` at the root of this project.
2. Install pnpm if you would like to follow 1:1 with the tutorial:
   1. Run: `pnpm i`
      1. If you are using another package manager install the package.json dependencies as you would normally.
3. Startup the local dev build by running:
   1. `pnpm dev`

## Usage

The intent of this repository is to serve as a primer for NextJS.

## Support

Reach out to me on Slack if you have any questions.

## Roadmap

This repository will cover all of the tpics found in the [NextJS Dashboard tutorial](https://nextjs.org/learn/dashboard-app/css-styling)

## Authors and acknowledgment

* Laszlo Lazuer
