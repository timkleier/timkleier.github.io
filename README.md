# Tim Kleier - Astro Site

## Start Development Server
To run the development server and preview your project locally, use the following command:

```bash
npm run start
```
This will start the development server and open a browser window with your site.

## Create Post
In the `src/content/blog` folder, create a new Markdown file and add content like this example:
```
---
title: "Ubiquitous <Programming> Language"
description: 'Ubiquitous Language in Domain-Driven Design provides a common language among humans, but we also need to create a common language among computers. This article explores a high-level approach to shared language across computer systems.'
pubDate: "Oct 1 2023"
---

Ubiquitous Language in Domain-Driven Design provides a common language among humans, but we also need to create a common language among computers. This article explores a high-level approach to shared language across computer systems.

[View the article](https://medium.com/@timkleier/ubiquitous-programming-language-4a8c80cd288e)

```

## Deployment
Deploying the site to timkleier.github.io is as simple as pushing a commit, which triggers a GitHub action to publish the site. 

