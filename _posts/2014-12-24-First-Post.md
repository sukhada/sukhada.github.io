---
layout: post
title: my first post!
---

So I've decided to start a blog, and so appropriately, I thought I'd write about how I created this blog as my first post.

If you haven't already heard of Github Pages, it's a super useful way to host a static webpage for free, using Github. They have great documentation about how to create your own Github Page [here](https://pages.github.com/).

Once I had that set up, I used [Jekyll Now](https://github.com/barryclark/jekyll-now) to create my blog. First, I forked the [Jekyll Now](https://github.com/barryclark/jekyll-now) repository, and renamed the repository to `mygithubusername.github.io`, and I was immediately able to see the following on my Github Page:

![Yay, you have a blog!]({{site.base_url}}/assets/initial_jekyll_now_page.png "Initial blog home page")

Next, I updated the `_config.yml` file with my name and my social network accounts. Then all I had to do was update the markdown post in the `_posts` folder with my post, and my first blog post was complete!

It was also fairly simple to make CSS changes that made the blog match more with my current website - I just had to switch out the `styles.scss` stylesheet with one of my own. 