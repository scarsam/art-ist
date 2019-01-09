---
title: 'Blogg'
views:
  main:
    template: anax/v2/article/default
    data:
      class: blog

  byline: false
  block-about: false
  article-toc: false

  blog-list:
    region: main
    template: anax/v2/blog-list/default
    sort: 2
    data:
      dateFormat: j F Y
      meta:
        type: toc
        orderby: publishTime
        orderorder: desc

  blog-toc:
    region: sidebar-right
    template: anax/v2/blog-toc/default
    sort: 2
    data:
      meta:
        type: copy
        view: blog-list
---

# Art Ist Blogg

Här får ni följa mig under min resa som artist. Allt från tankar om vardagen till enklare svar på frågor ni har till mig.
