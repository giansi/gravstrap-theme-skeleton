---
title: Home single
metadata:
  description: Gravstrap Theme helps you to start a new Grav CMS site with Bootstrap support and several ready to use modules. It is also perfect to extend to start a new Bootstrap custom theme, to fit your needs.
slug: gravstrap-theme-simple-page-example

content:
    items: @self.modular
    order:
        by: default
        dir: asc
        custom:
            - _showcase
            - _what_we_do
            - _portfolio
            - _clients
            - _team
            - _where_we_are
            - _contacts
---

[bootstrap-navbar id=navbar2 fixed=top centering=none brand_text="Gravstrap theme" render=false]
    [bootstrap-navbar-menu id=menu_0 alignment="center" submenu="internal" onepage=true][/bootstrap-navbar-menu]    
    [bootstrap-navbar-menu id=menu_1 icon_type="fontawesome" alignment="right" attributes="class: my-class,rel:my-rel"]
        [link url="https://facebook.com" icon="facebook"][/link]
        [link url="https://twitter.com" icon="twitter"][/link]
        [link url="http://my-rss.com" icon="rss"][/link]
    [/bootstrap-navbar-menu]
[/bootstrap-navbar]

[bootstrap-jumbotron id="jumbotron1" fullwidth="true" image="bg.jpg" render=false]
# Gravstrap theme

Gravstrap Theme helps you to start a new Grav CMS site with Bootstrap support and several ready to use modules. It is also perfect to start a new Bootstrap custom theme, to create your unique design.

[Download Gravstrap](https://github.com/giansi/gravstrap-theme-skeleton/releases){.btn .btn-outline-inverse .btn-lg}
[Learn Gravstrap](http://diblas.net/themes/gravstrap-theme-helps-to-start-a-new-grav-cms-site-with-bootstrap-support){.btn .btn-outline-inverse .btn-lg}
[/bootstrap-jumbotron]

