---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

---

<div id="introduction">
    <p class="intro-text center-content">&lt;<span class="html-tag">h1</span>&gt;James Gammon&lt;<span class="html-tag">/h1</span>&gt;</p>
    <p class="secondary-text center-content">&lt;<span class="html-tag">div class="Welcome to my page!"</span>&gt;</p>
    <p class="center-content">&lt;<span class="html-tag">p</span>&gt;I'm a Computer Science undergraduate, here you can find my portfolio and associated blogs.&lt;<span class="html-tag">/p</span>&gt;</p>
    <p class="secondary-text center-content">&lt;<span class="html-tag">/div</span>&gt;</p>
</div>

<br>


<p class="no-padding-paragraph" style="font-size: 26px">Projects:</p> 
<div class="center-content">
    <div class="bordered-text center-content">
        <a class="no-padding-paragraph headertut" href="/About-website.html">This website</a><br>
        <span class="post-meta">A simple combination of a personal portfolio and some inspired blogs; hosted on a single site.</span>
    </div>
</div>

<br>
<div class="center-content">
 <a href="https://github.com/jamesgammo">
    <picture>
      <source srcset="/github.png">
      <img src="github.png">
    </picture>
    <br/>
    <small class="headertut">GitHub</small>
  </a>
</div>

<br>

<p class="no-padding-paragraph" style="font-size: 26px">Recent Blog Posts:</p> 

<div id="blog posts"  class="center-content">
    <ul class = "older-posts">
        {%- assign last_cs = site.posts | where: "category", "CS" | first -%}
        {%- assign last_food = site.posts | where: "category", "Food" | first -%}
        <a class="no-padding-paragraph headertut" href="/code/">JG.Computing</a> 
        <li>
            <a class="post-link-tech" href="{{ last_cs.url }}">{{ last_cs.title }}</a>
            {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
            <span class="post-meta">{{ last_cs.date | date: date_format }}</span>
        </li>
        <br>
        <a class="no-padding-paragraph headertut" href="/food/">JG.Food</a> 
        <li>
            <a class="post-link-food" href="{{ last_food.url }}">{{ last_food.title }}</a>
            {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
            <span class="post-meta">{{ last_food.date | date: date_format }}</span>
        </li>
    </ul>
</div>


