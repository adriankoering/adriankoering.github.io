---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>
