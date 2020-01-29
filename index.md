---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      Welcome to my blog. I write articles on data science and software development.
  - section_id: about
    component: content_block.html
    type: contentblock
    title: About
    content: >-
      I'm a data scientist based in India. I have a strong passion towards software development and data engineering. I love making new projects and contributing towards open source software development. 
    actions:
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: posts_block.html
    type: postsblock
    title: Recent Posts
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
menus:
  main:
    weight: 1
    title: Home
layout: home
---
