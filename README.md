# NextJS Primer for the FS Team

## Name

Chapter 15 - Adding Authentication

---

[Deployment Link](https://nextjs-dashboard-two-rho-68.vercel.app/)

---

## This chapter will cover

* What is authentication.
* How to add authentication to your app using NextAuth.js.
* How to use Middleware to redirect users and protect your routes.
* How to use React's `useActionState` to handle pending states and form errors.

### What is authentication?

Authentication is a key part of many web applications today. It's how a system checks if the user is who they say they are.

A secure website often uses multiple ways to check a user's identity. For instance, after entering your username and password, the site may send a verification code to your device or use an external app like Google Authenticator. This 2-factor authentication (2FA) helps increase security. Even if someone learns your password, they can't access your account without your unique token.

### Authentication vs. Authorization

In web development, authentication and authorization serve different roles:

* **Authentication** is about making sure the user is who they say they are. You're proving your identity with something you have like a username and password.
* **Authorization** is the next step. Once a user's identity is confirmed, authorization decides what parts of the application they are allowed to use.
So, authentication checks who you are, and authorization determines what you can do or access in the application.

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
