---
layout: home-food
title: "Food blog"
category: Food 
order: 3
---
<script>
    // On page load
    document.addEventListener('DOMContentLoaded', function () {
        // Select all dropdown links
        const dropdownLinks = document.querySelectorAll('.dropdown-link');
        // For each link create function identifying the target div nad change the display property
        dropdownLinks.forEach(function (link) {
            link.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = link.getAttribute('data-target');
                const targetDropdown = document.getElementById(targetId);

                if (targetDropdown.style.display === 'none' || targetDropdown.style.display === '') {
                    // Display the dropdown content
                    targetDropdown.style.display = 'block';
                } else {
                    // Hide the dropdown content
                    targetDropdown.style.display = 'none';
                }
            });
        });
    });
</script>




<div id="introdction ">
    <!--Heading-->
    <p id="title" class="no-padding-paragraph center-content" style="font-size:24px;">Hi, I'm James</p>
    <!--Introduction to the blog-->
    <div id="blog-blurb">
        <p>I'm someone who's in an incredibly unique food allergy situation, and have turned to a blog to primarily help others with insights and information.</p>
    </div>
    <!--More information about the blog-->
    <div id="about-blog">
            <!--About me-->
            <img src="/windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">
            <a href="#" class="dropdown-link no-padding-paragraph" data-target="dropdown-1">About Me</a>
            <div class="dropdown-content" id="dropdown-1">
                <p>This is the content for Dropdown 1. It can contain any HTML content you want.</p>
            </div>
            <br>
            <!--Reasons to start the blog-->
            <img src="/windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">
            <a href="#" class="dropdown-link no-padding-paragraph" data-target="dropdown-2">Reasons starting the blog</a>
            <div class="dropdown-content" id="dropdown-2">
                <p>This is the content for Dropdown 2. It can contain any HTML content you want.</p>
            </div> 
            <br>           
            <!--What I aim to post about-->
            <img src="/windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">
            <a href="#" class="dropdown-link no-padding-paragraph" data-target="dropdown-3">Aim to post about</a>
            <div class="dropdown-content" id="dropdown-3">
                <p>This is the content for Dropdown 3. It can contain any HTML content you want.</p>
            </div>
            <br>
            <!--Navigating the blog-->
            <img src="/windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">            
            <a href="#" class="dropdown-link no-padding-paragraph" data-target="dropdown-4">Navigating the blog</a>
            <div class="dropdown-content" id="dropdown-4">
                <p>This is the content for Dropdown 4. It can contain any HTML content you want.</p>
            </div>
            <br>            
    </div>
</div>

<hr style="background-color: #4a8259; height: 1px; border: none;">  