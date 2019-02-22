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
   `bundle exec jekyll serve`
5. Now browse to `http://localhost:4000`