# PacMen-Exercise
First create index.html
Inside html create an div id = 'game'. 
Inside div create two buttons which are:
Add PacMen and Start Game.
Then create script in which you can call ./pacmen.js/.
Create pacmen.js
Declare position, direction and insert images in which PacMen are there.
create an empty array which holds all pacmen.
Use function setToRandom(scale){}
Use function makePac(){} to make PacMen at random position with random velocity it consists of:
velocity, position
Add img to div id = game
Get Html code by using getElementById then create new name called newing and  element called img and add position, src, width.
Set positon regarding in which way PanMen moves, append new Child to game. Return position, velocity newing.
Use function update(){} to perform loop over pacmen array and move each one and image in DOM. Use setTimeout.
Use function checkcollisions(items){} to detect collision with all walls and make pacmen bounce.
Use function makeOne(){} to add new PacMen.
