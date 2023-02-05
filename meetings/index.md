---
title: HOA Meetings
---

## HOA Meetings

The next meeting of the Applewood HOA will occur in Q2 2023.

## Meeting Minutes

<ul class="posts">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}" title="{{ post.title }}">
      {{ post.title }} - {{ post.date | date_to_string }}
    </a>
    <div class="clearboth"></div>
  </li>
{% endfor %}
</ul>
