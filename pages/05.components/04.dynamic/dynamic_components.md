---
title: Dynamic components
metadata:
  description: Gravstrap Theme helps you to start a new Grav CMS site with Bootstrap support and several ready to use modules. It is also perfect to extend to start a new Bootstrap custom theme, to fit your needs.
slug: dynamic-bootstrap-components-as-shortcodes-for-grav-cms

simple_form:
        token: "xxxxx"
        template_file: default
        redirect_to: /thank-you-for-my-page

googlemaps:
    map:
        center: 41.90278, 12.49637
        zoom: 12
        #type: TERRAIN
        markers:
            - location: 41.90278, 12.49637
              title: Gravstrap Theme
              zIndex: 1
              timeout: 1000
              info: <strong>Meet Us</strong>.<br/>We are there!

highlight:
    theme: ir_black
---


[gravstrap-jumbotron name="jumbotron1" fullwidth="true" image="bg.jpg" render=false]
# Gravstrap theme

Gravstrap Theme helps you to start a new Grav CMS site with Bootstrap support and several ready to use modules. It is also perfect to start a new Bootstrap custom theme, to create your unique design.

[Download Gravstrap Theme](https://github.com/giansi/gravstrap-theme-skeleton/releases){.btn .btn-outline-inverse .btn-lg}
[Learn Gravstrap](http://diblas.net/plugins/use-bootstrap-components-as-shortcodes-in-grav-cms){.btn .btn-outline-inverse .btn-lg}

[/gravstrap-jumbotron]

# Bootstrap components dynamically rendered by template
You can render the most of the Bootstrap components dynamically. Here you will find the example code for those components.
