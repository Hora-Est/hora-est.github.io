---
tags: []
---
<div itemscope itemtype="http://schema.org/Photograph">
  <h1>{{site.data.Cloudinary['2009']['04-29_pre-queensday_drink'].short_name}}</h1>
  <h2 class="event-date">{{site.data.Cloudinary['2009']['04-29_pre-queensday_drink'].date}}</h2>
  {% for url in site.data.Cloudinary['2009']['04-29_pre-queensday_drink'].urls %}
    <a itemprop="image" class="swipebox" title="" href="{{ site.cloudinary.baseurl }}/{{ url }}">
      <img alt="" itemprop="thumbnailUrl" src="{{ site.cloudinary.baseurl }}/h_150/{{ url }}" />
      <meta itemprop="isFamilyFriendly" content="true" />
    </a>
  {% endfor %}
</div>
