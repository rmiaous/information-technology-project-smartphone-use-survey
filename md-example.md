---
layout: page
title: Analysis Data page example
subtitle: Subtitle goes here
bigimg: /img/start.jpg
---

## Here is where we can insert an image:

![Smartphone Use Survey logo](/img/921581361.jpeg)

## How about a link?

And of course some text, and maybe [a link to https://forms.gle/FG96YjPS3AR9i6TXA](https://forms.gle/FG96YjPS3AR9i6TXA)

## Or some code?

Some code might go here:

```
x <- 5 # Here's some R code
```

What if I just paste the HTML for a plotly plot?

We can do it with a line of markdown that looks like this (without the slashes - I haven't solved that problem just yet...):
```
\{\% include jupyter-basic_bar.html \%\}
```
{% include jupyter-basic_bar.html %}

Attempting to embed an RShiny app:

<div class="iframe_container">
  <iframe width="800" height="700" scrolling="yes" frameborder="no"  src="https://kerchner.shinyapps.io/rshiny-test/"> </iframe>
</div>
