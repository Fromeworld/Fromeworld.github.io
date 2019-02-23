---
layout: page
title: Github pages
permalink: /github-pages/
---

<https://jekyllrb.com/docs/github-pages/>

github-pages seems nedd jekyll 3.7.4 (19.2.22)
    <https://github.com/github/pages-gem/issues/577>
`gem install jekyll -v 3.7.3`

Setting up your github pages site locally with Jekyll
    <https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll>

Adding Jekyll plugins to a Github pages site
    <https://help.github.com/en/articles/adding-jekyll-plugins-to-a-github-pages-site>

Layout
    <https://jekyllrb.com/docs/step-by-step/04-layouts/>
    minimal theme
    <https://github.com/jekyll/minima>
    comment
    <https://desiredpersona.com/disqus-comments-jekyll/>

Cheat sheet
    <https://devhints.io/jekyll>

```bash
./
├── _config.yml
│
├── _data/
│   └── ...
│
├── _drafts/
│   └── ...
│
├── _posts/
│   └── 2014-01-01-hello.md
│
├── _layouts/
│   ├── default.html
│   └── post.html
│
├── _includes/             - partials
│   ├── header.html
│   └── footer.html
│
└── _site/
    └── ...
```