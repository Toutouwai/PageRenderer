# Page Renderer

A module for ProcessWire CMS/CMF. Renders pages that have a template file. The module can be used for purposes such as pre-generating image variations across all the pages in a website, but in general it won't be useful to most people.

![2018-12-17_180739](https://user-images.githubusercontent.com/1538852/50067644-b8907b00-0226-11e9-8b6f-d2879c4d9212.png)

## Config options

* You can enter a selector to limit the pages that will be rendered. If the selector is left empty then all pages that have a template file will be rendered.

* There are options for rendering the pagination pages of templates that allow page numbers. You can choose between rendering a fixed number of pagination pages for a template or enter the number of child pages shown per pagination page and the module will calculate the number of pagination pages to render.

## Hookable method

There is a hookable `renderPage()` method. You might decide to use a replacement hook on this method if you want to do something such as render some URL segments for a page.
