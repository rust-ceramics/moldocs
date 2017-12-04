# Markdown Template Engine

## pulldown-cmark
Pull parser for [CommonMark](http://commonmark.org/).

It can render to HTML and maybe easy to use from as a library.

It is designed to be:

- Fast; a bare minimum of allocation and copying
- Safe; written in pure Rust with no unsafe blocks
- Versatile; in particular source-maps are supported
- Correct; the goal is 100% compliance with the CommonMark spec

## maud
Although this is HTML template engine, HTML rendered from Markdown can be used to apply.
