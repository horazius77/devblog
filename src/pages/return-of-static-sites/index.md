---
title: The Static Site Awakens and Strikes Back
date: "2020-01-17"
featuredImage: "./jamstack.jpeg"
---

Static Sites are returning and there are new technologies emerging with them. I will introduce some of them here.

<!-- end -->

`Work in progress`

I smiled when I read the first chapter of a [blogpost](https://www.sitepoint.com/7-reasons-use-static-site-generator/) with the headline _What is a Static Site?_ I bet 30 years ago somewhere was a blogpost with the introduction question _What is a Dynamic Site?_. Sometimes we forget how it all started.

Like me maybe you have already heard of netlify, JAMStack, Gatsby, next.js or nuxt.js but could not really bring it into context with server side rendering and static site generators. I will try to bring these in order here.

# client site rendering

SPA's built with Frameworks like Angular, React or Vue deliver the index.html with a reference to the app.js bundle application. The websites are then rendered via javascript on the client.

# server site rendering

Based on Backend with express.js as a webserver for node the dynamic sites are rendered on the server "on the fly".

## Next.js

Server site rendering for React applications.

## Nuxt.js

Server site rendering for Vue.js applications. Obviously inspired by Next.js.

# static site generators

The sites are prerendered during the build process.

> All content must therefore be available at build time. How do modern SSGs handle dynamic content like API-Requests and User input?

## Gatsby

Site generator built in React.

> Can Gatsby also be called to be a server site rendering framework? What is the difference between Gatsby and Next.js?

# Evolution of Architecture

The trend of static websites is accompanied by a stack acronym: JAM. Follow the history of the most important Stack-Acronyms below.

## LAMP (ca. 1998)

**L**inux, **A**pache, **M**ySQL, **P**HP

## MEAN (ca. 2013)

**M**ongoDB, **E**xpress.js, **A**ngular, **N**ode.js

## JAM (ca. 2016)

client-side **J**avaScript, reusable **A**PIs, **m**arkup

# Netlify

The inventors of JAM. Support the hosting of your JAM-Stack based application very good.
