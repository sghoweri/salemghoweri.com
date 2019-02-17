---
title: José's First Dev Huddle!
description: Kicking Off José's Adventures into Front End Development 
date: 2019-02-17
tags:
  - dev-huddle
  - consulting
layout: layouts/post.njk
---

## What We Covered!
- Reviewed high level front-end development goals for the next couple months
- Quick tour of José's current front-end dev workflow
- Walked through some intro HTML anatomy of current website
  - Reviewed HTML tags in his personal site's <head>
  - Also reviewed how <a> tags can link to other HTML tags on a page by using an `href="#blog-post"` on the anchor (with `blog-post` being the id on the element to jump to. ex. `<div id="blog-post"></div>`)
- Discussed how making site-wide changes (such as a change to the global site header), doesn't scale when you have to copy and paste the same change over and over
- Installed SourceTree, NodeJS, and Git Bash on José's Windows 10 computer
- Setup an SSH Key + added SSH creds to Github
- Connected SourceTree to José's Github account
- Used Git to clone down a copy of José's personal site so any code changes will be tracked moving forward
- Began reorganizing José's personal site into a `src` and `dist` folder so we can begin to break apart the UI into smaller reusable pieces + introduce tools to help take these templates, content, and components and assemble them into the fully working website
- Moved these WIP files to the `feature/refactor` branch + made José's first commit to Github (via SourceTree) + pushed up his first feature branch!
- Discussed homework for next week: find some inspirational sites / blogs with designs to aspire towards

## What's Up Next Up?
- Review any questions
- Discuss any inspiration websites, blogs, etc to begin to identify a visual direction to move towards
- Continue working on reorganizing blog codebase
  - Introduce Gulp + a package.json file as some simple front-end tools for managing the codebase