---
layout: post_code
title:  "A rock programming language?!"
date:   2023-11-20 11:56:06 +0100
category: CS
---
Why on earth does the rock have a programming language? 

Unfortunately Dwanye the rock does not have a programming language, nor do I think he's that interested to ever read this blog. If you are Dwayne, Love you in the fast and furious franchise. 


On a serious note, Upon listening to the Art of Code by Dylan Beattie, his creation of a rock programming language utterly blew me away. Not only because he created a programming language which is as impressive as it is, but he combines this with rock music, another thing I absoloutely adore. Now My interest in rock originated from my Dad playing it in the car, telling me "It's part of my education" and for Dylan to combine the two is beyond anything I could've imagined in the scope of fun projects. 

<a class="no-padding-paragraph headertut" href="https://codewithrockstar.com/">Website for rockstar</a><br>

<h1 style="font-family: 'Share Tech Mono'">Here is the source code</h1>

<p>Midnight takes your heart and your soul<br>
While your heart is as high as your soul<br>
Put your heart without your soul into your heart</p>
<p>Give back your heart</p>
<p>Desire is a lovestruck ladykiller<br>
My world is nothing<br>
Fire is ice<br>
Hate is water<br>
Until my world is Desire,<br>
Build my world up</p>
<p>If Midnight taking my world, Fire is nothing and Midnight taking my world, Hate is nothing<br>
Shout "FizzBuzz!"<br>
Take it to the top</p>
<p>If Midnight taking my world, Fire is nothing<br>
Shout "Fizz!"<br>
Take it to the top</p>
<p>If Midnight taking my world, Hate is nothing<br>
Say "Buzz!"<br>
Take it to the top</p>
<p>Whisper my world</p>

<h1 style="font-family: 'Share Tech Mono'">Here is the python transpiler</h1>

<pre>
def Midnight(your_heart, your_soul):
    while your_heart >= your_soul:
        your_heart = your_heart - your_soul
    return your_heart

Desire = 100
my_world = False
Fire = 3
Hate = 5
while not my_world == Desire:
    my_world += 1
    if Midnight(my_world, Fire) == False and Midnight(my_world, Hate) == False:
        print("FizzBuzz!")
        continue
    if Midnight(my_world, Fire) == False:
        print("Fizz!")
        continue
    if Midnight(my_world, Hate) == False:
        print("Buzz!")
        continue
print(my_world)
</pre>

<p>Now not only is this a badass rock song, the control structures 'is' defines a definiton, 'takes' defines a function and its associated paramters, and 'shout' is a print statement.</p>

<p>Now, Dylan come up with this in the pub, I cannot image sheer enjoyment you have of this compiling and it running, to shout FizzBuzz!! repeatidly. One day I'll create a language like this using Dwayne the Rock quotes, then that would really be ironic.</p> 