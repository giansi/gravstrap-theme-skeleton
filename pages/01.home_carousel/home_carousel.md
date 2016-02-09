---
title: Carousel header
menu: Carousel header
metadata:
  description: The Gravstrap theme home page with carousel header variation.
slug: home-page-with-carousel-header

gravstrap:
    jumbotron:
        jumbotron1:
            fullwidth: true
            from_file: jumbotron.markdown
            section: content
            image:
                name: bg.jpg

content:
    items: @self.modular
    order:
        by: default
        dir: asc
        custom:
            - _showcase
            - _intro
            - _what_we_do
            - _portfolio
            - _clients
            - _team
            - _where_we_are
            - _contacts
---

