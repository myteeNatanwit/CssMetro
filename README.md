Metro design
============
Screen shots:
http://i1363.photobucket.com/albums/r708/MyteeNathanwit/screenshot/metro_zps4323bb96.png
http://i1363.photobucket.com/albums/r708/MyteeNathanwit/screenshot/metro2_zpsa28af400.png

Metro source.
The idea of Metro is it comes in boxes, many colors, has a big logo, or big text. It runs on timer for animation like text scroll up, left, right etc... and finally, it scrolls horizontal like in Win8 shell. 
The metro is used in one of big project, together with other samples I submitted, you can put them together as in screen shots to form the UI project.

#The idea
When a programmer come across a web page, or an mobile app,  he right away works out in his mind "how this is done". That is the idea when we look at Metreo style of Win8. The source code is not well documented. Infact, it is not document at all for 2 reasons: 1- It is presented as plug in template, very easy to use. 2- Very simple Css code, user can always experiment with the template by playing with the Index.html file and related css. 

I must admit, I dont read user manual or instruction often, I play with the code. Rekon it helps better.

#Css

The css file is metro.css. 

There are many ways to get the effect. However, I prefer Css as my works always form the reusable templates. Css template is best for the reusable purpose.

1- We need to make a few tile classes that carry on the inheritance down to save the coding. title -> 2x -> 4x -> thin -> flat etc. For the project that this code designed, the tiles are transparent to see thru the video or image background. For demonstation purpose, we load an image to body background to see the hover n animation effect.

2- The horizontal div -vgroup- acts as a table helps for responsive design. Same screen can have several groups. If you resize the screen, the tiles will re-arrange to the new width.

3- 4 groups of tile color -vset 1 to 4- required as well as various type of icons. Color code/name is from http://www.w3schools.com/cssref/css_colornames.asp. Each Vgroup is assigned with different color set and layout.
I download the 64px icon set from http://dryicons.com/free-icons png format in different sets of size.
I use http://css.spritegen.com to make the sprites and css.
I make a wrapper to move the sprite class around. The trick is the parent box position must be relative, and the child sprite must be position:absolute.

4- Animation is for experiment as I am not confident about the cost of performance for the timer running in background. The Metro prototype I did submit to the project manager didnt have timer anyway.

5- The paging is for later step of sliding pages, it is for now only acting as a container, margin-top:120px, located right under the header.

6- There are style difined in the index.html, mainly for demonstration purpose. In your work, you dont have to keep any of them.

