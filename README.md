# NextJS Primer for the FS Team

## Name

Chapter 9 - Streaming

---

[Deployment Link](https://nextjs-dashboard-two-rho-68.vercel.app/)

---

## This chapter will cover

* What streaming is and when you might use it.
* How to implement streaming with `loading.tsx` and Suspense.
* What loading skeletons are.
* What route groups are, and when you might use them.
* Where to place Suspence boundaries in your application.

### What is Streaming?

* Streaming is a data transfer technique that allows you to break down a route into smaller "chunks" and progressively stream them from the server to the client as they become ready.
* By streaming, you can prevent slow data requests from blocking your whole page. This allows the user to see and interact with parts of the page without waiting for all the data to load before any UI can be shown to the user.
* Streaming works well with React's component model, as each component can be considered a chunk.

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
