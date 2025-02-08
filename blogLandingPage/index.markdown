---
layout: blogLandingPage
title: "Blog sitemap"
category: General 
order: 4 
navigation : true
---
<div>
    <!--- Insert cookie trail for site navigation here--->
    <p class="no-padding-paragraph" style="font-size: 30px">Sitemap</p>
    <hr class="hr-LandingPage"> 
    This is the sitemap, find blog posts and miscellanios stuff which may or may not be deserved to be eternalised on the internet forever. 
    <br><br>
    <div class="center-content">
        <img src="/rootMedia/windows cursor.png" alt="cursor" style="width: 20px; height: 20px;">
        <button id="random-post-button" class="no-padding-paragraph headertut">Go to a Random Post</button>
        <br><br>
        You will either want to read more, or click off. There is no imbertween
    </div>
    <br><br>
</div>
<div>
    <p class="no-padding-paragraph" style="font-size: 30px">Collections</p>
    <hr class="hr-LandingPage"> 
        There are collections and series. Each collection specifies the underlying theme of the blog post, and the series is more granular grouping.
    <div class="row">
        <div class="col col-1-33">
            <img src="/rootMedia/windows cursor.png" alt="cursor" style="width: 20px; height: 20px;">
            <a class="no-padding-paragraph headertut-Landing-Page" href="/Technology/">Technology</a>
            <div>
                A sweet Technology/Computing related blog where I share ideas, conceptualise relationships between computability and the outer world, and confuse myself alot.
            </div>
        </div>
        <div class="col col-2-33">
            <img src="/rootMedia/windows cursor.png" alt="cursor" style="width: 20px; height: 20px;">
            <a class="no-padding-paragraph headertut-Landing-Page" href="/Cology/">The cologies</a>
            <div>
                There are too many different cologies. Whats the psy'<i>cology</i>' of that? Explore more here
            </div>
        </div>
        <div class="col col-3-33">
            <img src="/rootMedia/windows cursor.png" alt="cursor" style="width: 20px; height: 20px;">
            <a class="no-padding-paragraph headertut-Landing-Page" href="/Miscellaneous/">Miscellanios</a>
            <div>
                Geography? Design? Music? May be these, might not. Might be an overview of my thoughs on books/tv shows. It's not all serious don't forget.
            </div>
        </div>
    </div>
</div>

<script>
    // Assign array of blog post url's into the script
    const blogPosts = [
        {% for post in site.posts %}
            "{{ post.url }}"{% if forloop.last == false %},{% endif %}
        {% endfor %}
    ];

    // Javascript for choosing a random blog posts nad presenting to the user 
    document.getElementById('random-post-button').addEventListener('click', function() {
        const randomIndex = Math.floor(Math.random() * blogPosts.length);
        const randomPost = blogPosts[randomIndex];
        window.location.href = randomPost;
    });
</script>