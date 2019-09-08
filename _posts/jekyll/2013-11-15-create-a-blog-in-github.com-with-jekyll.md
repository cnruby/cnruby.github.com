---
layout: post
title: "创建基于jekyll框架的GitHub.com博客"
tagline: "Create a Blog in GitHub.com with jekyll"
description: ""
tags: [jekyll, blog, tool, GitHub]
category: tools
---
{% include JB/setup %}

## Quick Commands

    cd ~/GITROOT/cnruby
    git clone https://github.com/cnruby/cnruby.github.com
    cd cnruby.github.com
    bundle install
    bundle update github-pages
    bundle exec jekyll serve --watch --incremental
    open http://127.0.0.1:4000/
    git push origin master or GitHub Desktop >> Commit to master >> Menu >> Repository >> Push
