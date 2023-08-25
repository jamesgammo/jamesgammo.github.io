---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Home"
order: 1
---


Recent blog posts:


<ul class = "older-posts">
    {%- assign last_cs = site.posts | where: "category", "CS" | first -%}
    {%- assign last_food = site.posts | where: "category", "Food" | first -%}
    <p class="no-padding-paragraph" >JG.Computing</p>
    <li>
    <a class="post-link-tech" href="{{ last_cs.url }}">{{ last_cs.title }}</a>
    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    <span class="post-meta">{{ last_cs.date | date: date_format }}</span>
    </li>
    <br>
    <p class="no-padding-paragraph">JG.Food</p>
    <li>
    <a class="post-link-food" href="{{ last_food.url }}">{{ last_food.title }}</a>
    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    <span class="post-meta">{{ last_food.date | date: date_format }}</span>
    </li>
</ul>




