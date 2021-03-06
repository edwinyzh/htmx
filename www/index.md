---
layout: layout.njk
title: </> htmx - high power tools for html
---

<div class="dark-hero full-width" classes="add appear">
  <span class="logo dark">&lt;<a>/</a>&gt; <span class="no-mobile">htm<a>x</a></span></span>
  <sub class="no-mobile"><i>high power tools for HTML</i></sub>
</div>


## introduction

htmx is a set of HTML extensions give you to access to [AJAX](https://htmx.org/docs#ajax), 
[WebSockets](https://htmx.org/docs#websockets) and [Server Sent Events](https://htmx.org/docs#sse) 
via [attributes](https://htmx.org/reference#attributes), allowing you to build [modern UI](https://htmx.org/examples) with the [simplicity](https://en.wikipedia.org/wiki/HATEOAS) and 
[power](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm) of hypertext

htmx is small ([~7k min.gz'd](https://unpkg.com/htmx.org/dist/)), 
[dependency-free](https://github.com/bigskysoftware/htmx/blob/master/package.json),
[extendable](/extensions),
IE11 compatible & you can try it out quickly, without a huge rewrite

## quick start

```html
  <!-- Load from unpkg -->
  <script src="https://unpkg.com/htmx.org@0.0.4"></script>
  <!-- have a button POST a click via AJAX -->
  <button hx-post="/clicked" hx-swap="outerHTML">
    Click Me
  </button>
```

The [`hx-post`](https://htmx.org/attributes/hx-post) and [`hx-swap`](https://htmx.org/attributes/hx-swap) attributes tell htmx:

> "When a user clicks on this button, issue an AJAX request to /clicked, and replace the entire button with the response"

htmx is the successor to [intercooler.js](http://intercoolerjs.org)

## haiku

*javascript fatigue:<br/>
longing for a hypertext<br/>
already in hand*