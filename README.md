# NextJS Primer for the FS Team

## Name

Chapter 8 - Fetching Data

---

[Deployment Link](https://nextjs-dashboard-two-rho-68.vercel.app/)

---

* What static rendering is and how it can improve your application's performance.
* What dynamic rendering is and when to use it.
* Different approaches to make your dashboard dynamic.
* Simulate a slow data fetch to see what happens.

### What is Static Rendering?

With static rendering, data fetching and rendering happens on the server at build time (when you deploy) or when [revalidating data](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching-caching-and-revalidating#revalidating-data).

Whenever a user visits your application, the cached result is served. There are a couple of benefits of static rendering:

Faster Websites - Prerendered content can be cached and globally distributed. This ensures that users around the world can access your website's content more quickly and reliably.
Reduced Server Load - Because the content is cached, your server does not have to dynamically generate content for each user request.
SEO - Prerendered content is easier for search engine crawlers to index, as the content is already available when the page loads. This can lead to improved search engine rankings.
Static rendering is useful for UI with no data or data that is shared across users, such as a static blog post or a product page. It might not be a good fit for a dashboard that has personalized data which is regularly updated.

The opposite of static rendering is dynamic rendering.

### What is Dynamic Rendering?

**What is Dynamic Rendering?**
With dynamic rendering, content is rendered on the server for each user at request time (when the user visits the page). There are a couple of benefits of dynamic rendering:

* **Real-Time Data** - Dynamic rendering allows your application to display real-time or frequently updated data. This is ideal for applications where data changes often.
* **User-Specific Content** - It's easier to serve personalized content, such as dashboards or user profiles, and update the data based on user interaction.
* **Request Time Information** - Dynamic rendering allows you to access information that can only be known at request time, such as cookies or the URL search parameters.

#### Takeaway

With dynamic rendering, your application is only as fast as your slowest data fetch.

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
