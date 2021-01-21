# Markdown Wiki

A minimalist wiki sofware based on Markdown that is simple to install and manage.

## Features

- An editor with live preview
- `[[page-name]]` syntax for linking other pages in the wiki
- Simple, yet powerful macro system
- Ability to associate metadata to pages and run queries to get/list subset of pages

# Requirements

- The whole application should be a single executable, including all javascript, css and images
- Size of a typical page, including all loaded scripts and images, should be less than 100KB
- Mutli-tenant
- Stores the pages in a sqlite database, with optional support for Postgres

# Possible Technologies

- Golang
- Simple Javascript / elm-lang / vue.js (in the order of preference)
- [stuffbin](https://github.com/knadh/stuffbin)

## Inspiration

* https://jottit.com/
* https://hedgedoc.org/
* http://moinmo.in/
* http://github.com/infogami/infogami

We may reuse the Markdown Editor from HedgeDoc, wiki syntax from Jottit/infogami, Minimalism and customization of Jottit and the macros from Infogami.

## License

AGPL (?)