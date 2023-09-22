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
                <p>Hi, as your currently aware as it's posted all around the website my name is James, I'm a second year student at University who is in an extremely unique allergy situation, as far as I'm aware, below is the list of my currently known allergens.</p>
                <ul>
                    <li>Eggs</li>
                    <li>Tree nuts</li>
                    <li>Peanuts</li>
                    <li>Fish</li>
                    <li>Crustaceans</li>
                    <li>Seasame</li>
                    <li>Molluscs</li>
                </ul>
                <p>I'm suprised your still here after that long list; however I invite you to carry on reading otherwise, I would have spent countless hours fiddiling with the colours and layout of this blog - which don't look that different from how it started anyway.</p>
                <p>I'm pretty open and upfont about allergies, but I haven't always been to be fair. As I've grown older I've discoved that not only being in this situation is a great conversation point as people seem pretty interested (Hopefully I'm not imaginging they are and boring them to death) but when talking to other people with similar situations, its a real great common ground between two people.</p>
                <p>However, being here today and writing this blog means I haven't died from anaphylaxis - or natural causes - just yet, I can reflect just briefly about how having these has changed my philosiphy on food and other aspects of my life.</p>
                <ul>
                    <li><b>Perception of food: </b>Over the past year my perception of food has really identified itself as more functional rather than enjoyment, now I'm not sure whether because of having so many allergies this is an outcome or coping mechanism, but I currently aim to eat meals which are with high nutrients and vitamins benefitting my health, rather than the enjoyment of sitting down savouring the taste as such.</li>
                </ul>
                <ul>
                    <li><b>Risk taking: </b>Growing up eating may seem trivial to most, no risks apart from a upset stomach or risk of enjoying a 'bad' food too much, but when it's life or death over something as simple as french toast or peanut butter, my own perception to risk has greatly veered towards no reward is greater than the risk. I understand I've learn't this though food, but as I've gotten older I have become increasingly self aware of the avoid risk attitude. Now because of this, I'd make an awful investment banker. Luckily I study Computer Science - where my biggest risk is bad posture.</li>
                </ul>
                <ul>
                    <li><b>Confidence: </b>People say that throwing yourself in the deep end is the best way to learn, but I'm sure we can all agree the person who invented this saying, and whoever invented washing up, were nobodys favourites, but this doesn't take away from the fact of the statement. When talking in restaurants to waiters; baristas in cafes, one simple question about an allergy can be the difference of a great afternoon enjoying a meal, or a great loss of life of someone who was too afraid to ask; when faced with this ultimatium in some, but not all cases, I'm sure most people choose the former.</li>
                </ul>
            <p>Now I am fully aware that the paragraph around risk taking makes me sound boring, honestly I promise I'm not, living life to it's fullest and greatest is important to me, but the risk reward system in my brain has certainly been biasly trained.</p>
            </div>
            <br>
            <!--Reasons to start the blog-->
            <img src="/windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">
            <a href="#" class="dropdown-link no-padding-paragraph" data-target="dropdown-2">Reasons starting the blog</a>
            <div class="dropdown-content" id="dropdown-2">
                <p>Travelling is extremely enjoyable. It's exhilarating if you are going down a zip-wire at the eden project, fascinating if you are immersed in the Leonardo da Vinci museum in Venice and breath-taking if you're standing on the east ridge of the Grand Canyon. Preparing to go travelling in Europe was the small rock that created the avalanche for me to start this blog, one thing led to another now here I am procrastinating about doing some work, so I'm filling in this blog. The reason was funnily enough food allergies, freedom of information about a new experience, for me completely negates alot of anticipation, it was one food blog I read about travelling in Italy which enlightened me into thinking about the possibility of starting my own, obviously I can never run out of things to talk about from allergies, having 7 out of the big 14 I'm exactly half on a full house.</p>
            </div> 
            <br>           
            <!--What I aim to post about-->
            <img src="/windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">
            <a href="#" class="dropdown-link no-padding-paragraph" data-target="dropdown-3">Aim to post about</a>
            <div class="dropdown-content" id="dropdown-3">
                <p>I love to create and post, some big things I'll mainly be posting about are: 
                <ul>
                    <li>Travel</li>
                    <li>University</li>
                    <li>Everyday experience</li>
                    <li>Tips/Tricks</li>
                </ul>
                <p>Naturally posts will diverse out of these catagories, but these are the three diciplines most important to me.</p>
                </p>
            </div>
            <br>
            <!--Navigating the blog-->
            <img src="/windows cursor.png" alt="cursor" style="width: 20px; height; 20px;">            
            <a href="#" class="dropdown-link no-padding-paragraph" data-target="dropdown-4">Navigating the blog</a>
            <div class="dropdown-content" id="dropdown-4">
                <p>This is the home page, the most recent posts have an insight into what they include. Posts will be visually catagoried in a way I haven't come up with yet; At the end of each post will be a series of related posts.</p>
            </div>
            <br>            
    </div>
    <p class="no-padding-paragraph center-content">Thanks :D</p>

</div>

<hr style="background-color: #4a8259; height: 1px; border: none;">  