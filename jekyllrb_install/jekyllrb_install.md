---
layout: page
title: Install
permalink: /install/
---

<https://jekyllrb.com/docs/>

Requirement

1. Install Ruby `sudo apt install ruby ruby-dev`
2. Install gem (Installed automatically when install ruby)
3. Install gcc and make

Install Jekyll

1. `gem install jekyll bundler`
2. Create a new Jekyll site at `./myblog` by `jekyll new myblog`
3. `cd myblog`
4. Build the site and make it available on a local server
   `bundle exec jekyll serve` or `JEKYLL_ENV=production bundle exec jekyll`.
5. Now browse to `http://localhost:4000`

TODO list

1. [ok] add preview picture for blogs
2. [ok] add comment system, restrict to github user.
   <https://deepaksood619.github.io/technology/adding-comments-system-for-posts-in-jekyll/>
3. fix the position of the comment box at the bottom of each pages.
4. show tag