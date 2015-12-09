---
title: The internal template
metadata:
  description: A very versatile template to handle internal pages.

slug: the-internal-template-in-detail

columns:
    main:
        width: 6
        extra_classes: col-sm-12
    left:
        width: 3
        extra_classes: col-sm-12
    right:
        width: 3
        extra_classes: col-sm-12
---

# How to use the internal template
The internal template handles the website internal pages. This is a very versatile template because you can define the columns number and their width, in the page's header section, .

By default it comes as a two columns template, with a left sidebar and large content section. To add a third column, just configure the page's header section as follows:

    columns:
        main:
            width: 7
        left:
            width: 3
        right:
            width: 2

Usually you would also define the classes for small devices. This can be easily accomplished, adding an `extra_classes` attribute to the column definition:

    columns:
        main:
            width: 7
            extra_classes: col-sm-12
        left:
            width: 3
            extra_classes: col-sm-12
        right:
            width: 2
            extra_classes: col-sm-12

If you need a full page template, just configure the columns as follows:

    columns:
        main:
            width: 12
            extra_classes: col-sm-12
        left:
            width: 0
        right:
            width: 0

You can add a main offset column as follows:

If you need a full page template, just configure the columns as follows:

    columns:
        main:
            width: 8
            extra_classes: col-md-offset-2 col-sm-12
        left:
            width: 0
        right:
            width: 0
