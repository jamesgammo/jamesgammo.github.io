---
layout: home
---

<div id="introduction">
    <p class="intro-text center-content">James Gammon</p>
    <!-- Small description -->
    <div>
        <!----
        <div class="col">    
            <p class="secondary-text center-content">&lt;<span class="html-tag">div</span>&gt;</p>
        </div>
        --->
        <div class="col">
            <p class="center-content">&lt;<span class="html-tag">p</span>&gt;Hi, I'm an undergraduate Computer Scientist with a passion for creating and sharing ideas and information, and love being part of experiences where you turn and think "wow, that is cool!"&lt;<span class="html-tag">/p</span>&gt;</p>
        </div>
        <div id="SecondInfo">
            <p class="no-padding-paragraph">Links:</p>
            <li><img src="windows cursor.png" alt="cursor" style="width: 20px; height: 20px;"> :: This icon && <a class="headertut"> Hover cursor here</a></li>
            <p class="no-padding-paragraph">Posts:</p>
            <li>Post headings are bright and colourful and jump out when hovered over</li>
        </div>
        <br>
        <div id="ThirdInfo">
            <p class="center-content no-padding-paragraph" style="font-size:24px;">Scroll for blog posts, projects and my CV :D</p>
            <hr><br>
        </div>
    </div>
</div>
<!-- Blog posts -->
<p class="no-padding-paragraph" style="font-size: 26px">My recent blog posts:</p> 
<div id="blog posts"  class="center-content">
    <ul class = "older-posts">
        {%- assign last_cs = site.posts | where: "category", "CS" | first -%}
        {%- assign last_food = site.posts | where: "category", "Food" | first -%}
        <img src="windows cursor.png" alt="cursor" style="width: 20px; height: 20px;">
        <a class="no-padding-paragraph headertut" href="/code/">JG.Computing</a> 
        <li>
            <a class="post-link-tech" href="{{ last_cs.url }}">{{ last_cs.title }}</a>
            {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
            <span class="post-meta">{{ last_cs.date | date: date_format }}</span>
        </li>
        <br>
        <img src="windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">
        <a class="no-padding-paragraph headertut" href="/food/">JG.Food</a> 
        <li>
            <a class="post-link-food" href="{{ last_food.url }}">{{ last_food.title }}</a>
            {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
            <span class="post-meta">{{ last_food.date | date: date_format }}</span>
        </li>
    </ul>
</div>
<br>

<!-- Projects -->
<p class="no-padding-paragraph" style="font-size: 26px">Check out my projects:</p>
<br> 
<div class="center-content">
    <!-- Website project  -->
    <div class="bordered-text center-content">
        <a class="no-padding-paragraph headertut" href="/About-website.html">This website</a><br>
        <span class="post-meta">A simple combination of a personal portfolio and some inspired blogs; hosted on a single site</span>
    </div>
    <!-- Othello Game project  -->
    <div class="bordered-text center-content">
        <a class="no-padding-paragraph headertut" href="/about-othello.html">Othello</a><br>
        <span class="post-meta">A two player Othello game, written in Java using Java UI framework </span>
    </div>
    <br>
    <!-- Car racing game-->
    <div class="bordered-text center-content">
        <a class="no-padding-paragraph headertut" href="/about-racing.html">Single player racing game</a><br>
        <span class="post-meta">Car controller designed to teach and test racing principles</span>
    </div>
    <!-- C server development -->
    <div class="bordered-text center-content">
        <a class="no-padding-paragraph headertut" href="/about-cserver.html">C server implementation</a><br>
        <span class="post-meta">Network server using dijkstras and a network library to foward packets over TCP/IP</span>
    </div>
    <br>
</div>


<!-- Github symbol -->
<div class="center-content">
<p class="no-padding-paragraph" style="font-size: 20px"></p>
 <a href="https://github.com/jamesgammo">
    <picture>
      <source srcset="/github.png">
      <img src="github.png">
    </picture>
    <br/>
    <img src="windows cursor.png" alt="cursor" style="width: 17px; height; 17px;">
    <small class="headertut" style="font-size: 15px">GitHub</small>
  </a>
</div>
<div class="center-content">
<br><br>
<p class="no-padding-paragraph" style="font-size: 26px">Check out my CV     :</p>
    <object
        type="application/pdf"
        data="/JamesGammonCV.pdf"
        width="800"
        height="700"
        class="center-content"
    >
    </object>

</div>

<br>




