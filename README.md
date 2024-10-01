# NextJS Primer for the FS Team

## Name

Chapter 12 - Mutating Data

---

[Deployment Link](https://nextjs-dashboard-two-rho-68.vercel.app/)

---

## This chapter will cover

* What React Server Actions are and how to use them to mutate data.
* How to work with forms and Server Components.
* Best practices for working with the native `formData` object, including type validation.
* How to revalidate the client cache using the `revalidatePath` API.
* How to create dynamic route segments with specific IDs.

### What are Server Actions?

React Server Actions allow you to run asynchronous code directly on the server. They eliminate the need to create API endpoints to mutate your data. Instead, you write asynchronous functions that execute on the server and can be invoked from your Client or Server Components.

Security is a top priority for web applications, as they can be vulnerable to various threats. This is where Server Actions come in. They offer an effective security solution, protecting against different types of attacks, securing your data, and ensuring authorized access. Server Actions achieve this through techniques like POST requests, encrypted closures, strict input checks, error message hashing, and host restrictions, all working together to significantly enhance your app's safety.

### Next.js with Server Actions

Server Actions are also deeply integrated with Next.js [caching](https://nextjs.org/docs/app/building-your-application/caching). When a form is submitted through a Server Action, not only can you use the action to mutate data, but you can also revalidate the associated cache using APIs like `revalidatePath` and revalidateTag.

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
