---
layout: post
title: "Hello, world."
date: 2023-11-06 18:54:00 -0500
---

I have created this blog in order to track my growth in the tech field. I have been working as a Data Analyst for a little over one year now. My long term goal is to become a Software Developer. I am working hard at expanding my tech catalog, here are a few skills I have acquired so far.

- Python
- Javascript
- Typescript
- SQL
- AWS Quicksight
- Node
- React

---

With that being said I would like my first post to have some value. I shall share my experience creating this github pages site with jekyll.
To preface, I view this blog as a sort of stepping stone. I set the challenge to get this up with no videos, just documentation and forums.

### Creation

The documentation for getting a github pages site up with jekyll is very straight forward. Here is the [documentation][pages-doc] I followed.
However there were a few things I thought I would share here that had me scratching my head for a moment.

1. At first I had set up a USERNAME.github.io repo however this is for the base site USERNAME.github.io. What I wanted was USERNAME.github.io/blog. To do so I created a [blog repo][git-repo] and set the baseurl in my \_config.yml file to /blog.

2. Once I got my site up on my github repo I noticed the CSS was off for the site. It turns out I was missing a gem bundle. After looking at the deployment logs for the pages site I learned I needed to add the racc gem bundle to my project.
   > To do so run **bundle add racc** then **bundle exec jekyll serve**

If you have made it this far thank you for reading my first blog post. I hope it is able to be of use to someone that is stuck.

[pages-doc]: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll?platform=windows
[git-repo]: https://github.com/josrot/blog
