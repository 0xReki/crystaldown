---
title: Unreadable Scripts

date: 2020-02-05 01:11 +01:00
series: crystaldown
---
𝖄𝖔𝖚 𝖉𝖔𝖓'𝖙 𝖓𝖊𝖊𝖉 𝖙𝖔 𝖌𝖔 𝖙𝖔 “𝖊𝖝𝖔𝖙𝖎𝖈” 𝖑𝖆𝖓𝖌𝖚𝖆𝖌𝖊𝖘 𝖑𝖎𝖐𝖊 𝕽𝖚𝖘𝖘𝖎𝖆𝖓 𝖔𝖗 𝕵𝖆𝖕𝖆𝖓𝖊𝖘𝖊 𝖙𝖔 𝖓𝖔𝖙 𝖇𝖊𝖎𝖓𝖌 𝖆𝖇𝖑𝖊 𝖙𝖔 𝖗𝖊𝖆𝖉.
𝕳𝖆𝖛𝖊 𝖞𝖔𝖚 𝖊𝖛𝖊𝖗 𝖙𝖗𝖎𝖊𝖉 𝖗𝖊𝖆𝖉𝖎𝖓𝖌 𝕱𝖗𝖆𝖐𝖙𝖚𝖗?
𝕺𝖗 𝖊𝖛𝖊𝖓 𝖜𝖔𝖗𝖘𝖊, 𝕾𝖚𝖊𝖙𝖙𝖊𝖗𝖑𝖎𝖓 𝖑𝖊𝖙𝖙𝖊𝖗𝖘?

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 30
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
