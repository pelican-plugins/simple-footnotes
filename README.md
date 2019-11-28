Simple Footnotes
================

[![Build Status](https://img.shields.io/github/workflow/status/pelican-plugins/simple-footnotes/build)](https://github.com/pelican-plugins/simple-footnotes/actions) [![PyPI Version](https://img.shields.io/pypi/v/pelican-simple-footnotes)](https://pypi.org/project/pelican-simple-footnotes/)

Simple Footnotes is a Pelican plugin for adding footnotes to articles and pages.

Installation
------------

This plugin, and its dependent package `html5lib`, can be installed via:

    python -m pip install pelican-simple-footnotes

Usage
-----

When writing an article or page, add a footnote like this:

    Here’s my written text[ref]and here is a footnote[/ref].

This will appear as, roughly:

Here’s my written text<sup>1</sup>

 1. and here is a footnote ↩

This should work with any content format (reST, Markdown, et cetera), because
it looks for `[ref]` and `[/ref]` once the conversion to HTML has happened.

Contributing
------------

Contributions are welcome and much appreciated. Every little bit helps. You can contribute by improving the documentation, adding missing features, and fixing bugs. You can also help out by reviewing and commenting on [existing issues][].

To start contributing to this plugin, review the [Contributing to Pelican][] documentation, beginning with the **Contributing Code** section.

Credits
-------

Originally authored by [Stuart Langridge](https://kryogenix.org/), February 2014,
and subsequently enhanced by members of the Pelican community, including
[Justin Mayer](https://justinmayer.com/), who re-packaged it for publication to
PyPI.

Inspired by Andrew Nacin’s [Simple Footnotes WordPress plugin](https://wordpress.org/plugins/simple-footnotes/).


[existing issues]: https://github.com/pelican-plugins/simple-footnotes/issues
[Contributing to Pelican]: https://docs.getpelican.com/en/latest/contribute.html
