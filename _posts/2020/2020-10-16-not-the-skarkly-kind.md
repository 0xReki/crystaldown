---
title: "Not The Sparkly Kind"
---
Vampires in this story are not of the sparkly kind. At least, Patrick isn't.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 2
  | where: "chapter", 65
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
