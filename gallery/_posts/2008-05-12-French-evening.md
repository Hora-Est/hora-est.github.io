---
tags: []
---
<div itemscope itemtype="http://schema.org/Photograph">
  <h1>{{site.data.Cloudinary['2008']['05-12_french_evening'].short_name}}</h1>
  <h2 class="event-date">{{site.data.Cloudinary['2008']['05-12_french_evening'].date}}</h2>
  {% for url in site.data.Cloudinary['2008']['05-12_french_evening'].urls %}
    <a itemprop="image" class="swipebox" title="" href="{{ site.cloudinary.baseurl }}/{{ url }}">
      <img alt="" itemprop="thumbnailUrl" src="{{ site.cloudinary.baseurl }}/h_150/{{ url }}" />
      <meta itemprop="isFamilyFriendly" content="true" />
    </a>
  {% endfor %}
</div>
