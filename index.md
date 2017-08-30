---
layout: page
title: Essays
tagline: The Collection
---
{% include JB/setup %}


<!-- <ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul> -->

<table class="table condensed text-center">
  <tbody>
  {% for post in site.posts %}
    <tr>
      <td>{{ post.date | date_to_string }}</td>
      <td><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></td>
    </tr>
  {% endfor %}
  </tbody>
  </table>


