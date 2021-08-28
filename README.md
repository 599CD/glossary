# Glossary

[![Built With: DocFX](https://img.shields.io/badge/Built_With-DocFX-yellowgreen.svg)](https://dotnet.github.io/docfx/)

![599CD](images/599cd-logo.png "599CD Logo")

- [Current](https://www.599cd.com/glossary/)

## Guide

See the [Wiki](/wiki) for info on how to contribute.

### DocFX

- [Walkthrough Part I: Generate a Simple Documentation Website](https://dotnet.github.io/docfx/tutorial/walkthrough/walkthrough_create_a_docfx_project.html)

Pulled the source of this repo.

`docfx init -q`

Moved to root folder.

Updated [docfx.json](docfx.json)

Added favicon etc to the images folder.

Build `docfx docfx.json`

Run `docfx serve _site`

Build and Run `docfx docfx.json --serve`

- [Local](http://localhost:8080/)
- [Live](https://599cd.github.io/glossary)

## Deploy

The site is auto-deployed to [GitHub Pages](https://pages.github.com/) using [ci-cd.yml](.github/workflows/ci-cd.yml)
