---
views:
    kursrepo:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
---
Testing Markdown
====================

First, let's add an h2 heading
-------------------------------

### And and h3, while we're at it

It's simple to add a [link](https://daringfireball.net/projects/markdown/syntax "Markdown Syntax") without too much fuss.

It's even possible to create an implicit link name, such as:

    [dbwebb][]
which turns into [dbwebb][], provided that you define the link somewhere in your
document, by writing:

    [dbwebb]: http://dbwebb.se/


[dbwebb]: http://dbwebb.se/

There I also tested a code block.
