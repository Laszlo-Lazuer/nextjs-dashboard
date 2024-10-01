# NextJS Primer for the FS Team

## Name

Chapter 9 - Streaming

---

[Deployment Link](https://nextjs-dashboard-two-rho-68.vercel.app/)

---

## This chapter will cover

* What Partial Prerendering is.
* How Partial Prerendering works.

## Description

This repository will follow along with the NextJS Dashboard app [tutorial](https://nextjs.org/learn/dashboard-app) from the NextJS documentation. Each chapter of the tutorial is broken out as it's own branch. Incrementally building upon itself as the tutorial progresses.

### What is Partial Prerendering?

Next.js 14 introduced an experimental version of Partial Prerendering – a new rendering model that allows you to combine the benefits of static and dynamic rendering in the same route. For example:

#### When a user visits a route:
* A static route shell that includes the navbar and product information is served, ensuring a fast initial load.
* The shell leaves holes where dynamic content like the cart and recommended products will load in asynchronously.
* The async holes are streamed in parallel, reducing the overall load time of the page.

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
