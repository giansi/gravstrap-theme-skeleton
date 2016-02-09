## How to use the carousel as page header

This page uses the `Slideme carousel` as home page header. When you want to configure `Gravstrap Theme` to work this way, you need to do some small changes to your theme.

The very first thing to do is to extend the theme, as well explained in this [tutorial](http://getgrav.org/blog/theme-development-with-inheritance).

Next, copy the `user/themes/gravstrap-theme/templates/home.html.twig` template from gravstrap-theme to yours, under the same folder, open it and replace the following code:

    {% block header %}
    <header id="header">
        {{ gravstrap.jumbotron1 }}
        {{ gravstrap.navbar1 }}
    </header>
    {% endblock %}

as follows;

    {% block header %}
    {{ gravstrap.navbar1 }}
    {% endblock %}

This will override the default header and renders the website navbar.

To complete the configuration, open the `user/pages/home/modular/_showcase/showcase.md` file, set it to `fullscreen`, changing that property to true and `publish the page`, which is unpublished by default:

    ---
        title: Showcase
        fullwidth: true
        published: true

        [...]

and you are done.
___