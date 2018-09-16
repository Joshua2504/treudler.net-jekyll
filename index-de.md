---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /deutsch.html
header:
  image: /assets/img/header/2018-06-14-index.gif
excerpt: >
  
ref: home
lang: de
---

Du bist möglicherweise hier weil du wissen möchtest was mit Treudler passiert ist. Mein Statement ist [hier](dedication.html) und nur in Englisch verfügbar. Bei Gelegenheit und zu viel Freizeit veröffentliche ich auch eine deutsche Version.

*Bitte beachte, dass ich die deutsche Version meiner Internetpräsenz im Moment nicht aktualisiere. Rechts oben kannst du die Sprache ändern um so auf etwaige Inhalte wie künftige Blogeinträge, welche ausschließlich in Englisch zur Verfügung stehen, zuzugreifen.*

Das [Impressum](impressum.html) und eine [Kontaktmöglichkeit](kontakt.html) sind auch in deiner Sprache verfügbar.

<h2>Meine letzten Blogeinträge</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" %}


<ul class="tags">
{% for tag in post.tags %}
  <li><a href="/tags#{{ tag }}" class="tag">{{ tag }}</a></li>
{% endfor %}
</ul>