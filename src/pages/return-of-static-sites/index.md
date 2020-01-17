---
title: The Static Site Awakens and Strikes Back
date: "2020-01-17"
featuredImage: "./strikesback.png"
---

Static Sites are returning and there are new technologies emerging with them. I will introduce some of them here.

<!-- end -->

`Work in progress...`

I smiled when I read the first chapter of a [blogpost](https://www.sitepoint.com/7-reasons-use-static-site-generator/) with the headline _What is a Static Site?_ I bet 20 years ago somewhere was a blogpost with the introduction question _What is a Dynamic Site?_. Sometimes we forget how it all started.

Like me maybe you have already heard of netlify, JAMStack, Gatsby, next.js or nuxt.js but could not really bring it into context with server side rendering and static site generators. I will try to bring these in order here.

# client site rendering

SPA's built with Frameworks like Angular, React or Vue deliver the index.html with a reference to the app.js bundle application. The websites are then rendered via javascript on the client.

# server site rendering

Based on Backend with express.js as a webserver for node the dynamic sites are rendered on the server "on the fly".

## Next.js

Server site rendering for React applications.

## Nuxt.js

Server site rendering for Vue.js applications. Obviously inspired by Next.js.

# [static site generators](https://www.keycdn.com/support/static-site-generator)

The sites are prerendered during the build process.

> All content must therefore be available at build time. How do modern SSGs handle dynamic content like API-Requests and User input?

## Gatsby

Static Site generator built in React.

> Can Gatsby also be called to be a server site rendering framework? What is the difference between Gatsby and Next.js?

# Evolution of Architecture

The trend of static websites is accompanied by a stack acronym: JAM. Follow the history of the most important Stack-Acronyms below.

## LAMP (ca. 1998)

**L**inux, **A**pache, **M**ySQL, **P**HP

## MEAN (ca. 2013)

**M**ongoDB, **E**xpress.js, **A**ngular, **N**ode.js

## [JAM](https://jamstack.org/) (ca. 2016)

client-side **J**avaScript, reusable **A**PIs, **m**arkup

# Netlify

The inventors of JAM. Support the hosting of your JAM-Stack based application very good.

# Why? My two cent...

One reason is of course the performance and better security of static websites about which has already been sufficiently written about. But another reason is the possibility to include the content providing non technical savy user.

With version control and CI/CD Pipelines Software developers have sophisticated tools and processes for code maintenance and deployments. These tools were not used by non technical savy people who had to use Content Mangement Systems like Wordpress, Joomla, Drupal or TYPO3 to provide their content.

With easy to use tools and cloud based version control and CI/CD pipelines these users can now benefit from the same processes.

## Git based CMS System

Here is an example stack for a new kind of CMS System:

-   [DevBlog](https://ryanfitzgerald.github.io/devblog/) is a blog template based on GatsbyJS. Create your own branch in GitHub.
-   The application can then be hosted at netlify. Commits to the master branch will automatically deploy the site.
-   Content providing users can create new blogposts via [StackEdit](https://stackedit.io/). They need their own github account and can deploy new markdown files as blogposts to githubb
    -   You can let the users push directly to master branch, or
    -   you can of course use same rules as usual like no pushes to master branch without pull requests.

## Headless CMS System

Netlify CMS is a so called headless CMS System.

> How does it compare to git based CMS System above?
