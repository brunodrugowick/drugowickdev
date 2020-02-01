---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      I love helping people to understand and deal with technology. 
      If I can build something in the process, even better!
  - section_id: about
    component: content_block.html
    type: contentblock
    title: About
    content: >-
      This is my personal website and blog. The blog mirrors my content from [dev.to](https://dev.to/brunodrugowick). I write about what I read. I read what I want to learn. I learn by doing!
      
      Currently I'm reading and learning about Spring, RESTful, APIs, JPA, Spring Data, Microservices etc.
      
      I'm a learner, help me interacting and teaching me. Everyone has something to say, everyone has a story to tell.
    actions:
      - label: More About Me
        url: /about
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
