Simple Footnotes
================

[![Build Status](https://github.com/pelican-plugins/simple-footnotes/workflows/build/badge.svg)](https://github.com/pelican-plugins/simple-footnotes/actions)

Simple Footnotes is a Pelican plugin for adding footnotes to articles and pages.

Installation
------------

This plugin, and its dependent package `html5lib`, can be installed via:

    pip install pelican-simple-footnotes

Usage
-----

When writing an article or page, add a footnote like this:

    Here’s my written text[ref]and here is a footnote[/ref].

This will appear as, roughly:

Here’s my written text<sup>1</sup>

 1. and here is a footnote ↩

This should work with any content format (reST, Markdown, et cetera), because
it looks for `[ref]` and `[/ref]` once the conversion to HTML has happened.

Development
-----------

Contributions are welcome and much appreciated. See [CONTRIBUTING.md][] for more
information.

Credits
-------

Originally authored by [Stuart Langridge](https://kryogenix.org/), February 2014,
and subsequently enhanced by members of the Pelican community, including
[Justin Mayer](https://justinmayer.com/), who re-packaged it for publication to
PyPI.

Inspired by Andrew Nacin’s [Simple Footnotes WordPress plugin](https://wordpress.org/plugins/simple-footnotes/).


[CONTRIBUTING.md]: https://github.com/pelican-plugins/simple-footnotes/blob/master/CONTRIBUTING.md
