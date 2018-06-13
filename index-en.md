---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /index.html
header:
  image: /assets/img/header/2018-03-31-bremerhaven-hw-desc.jpg
tagline: > # this means to ignore newlines until "repository:"
  Moin moin!
excerpt: >

ref: home
lang: en
---

If you want to know what has happened to Treudler, my hosting company, [click here](dedication.html).

This page is also available in [Deutsch](deutsch.html), but I don't really maintain the german version at this time as I'm busy with other things.

Some blog posts might only be available in german at this time, but I'm trying to translate them to english as soon as possible. Check the [german](deutsch.html) website to find more posts.

<h2>My latest blog posts</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" %}

