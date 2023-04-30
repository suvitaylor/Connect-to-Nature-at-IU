---
layout: page
permalink: /exhibits/
title: Exhibit A: Campus Life as a Student (Springtime edition) 
---

A main focus of this exhibition is to show students that there is nature all across campus. It was great to walk around Dunn Meadow and see everyone hammocking, having a picnic, play frisbee, etc. in early April. I chose that photo for this Exhibit because I think it sums up what it is like to be a college students enjoying a warm day. There is a sense of conntectness that students have after living on one campus for many years. Being in nature and warm weather seems to create an even larger sense of community. 


{% assign exhibits = site.exhibits | where: 'layout','exhibit' %}
<ul>
  {% for exhibit in exhibits %}
    <li>
      <a href='{{ exhibit.url | absolute_url }}'>
        {{ exhibit.title }}
      </a>
    </li>
  {% endfor %}
</ul>
