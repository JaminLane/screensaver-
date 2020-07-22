# screensaver-
For my screensaver project I wanted to be able to create a changing background with a ball moving about the screen. When I created my code I tried to make the background first and I believe this is what gave me problems. When I went to add the ball to move about the screen I could never figure out how to make it appear before the background instead of behind it. My belief is that it is stuck behind because the program is running on a loop. Either way im proud of what I have made and would make it my own background! 

Here is the link to the website to view the project 

https://editor.p5js.org/jlane3/sketches/CN7Ee0mUT

Here is my code for the screensaver: 
function setup() {
  createCanvas(800, 600);
  frameRate(1)
  x= width/2;
  y=height;
}

  
function draw() {
  {stroke(50);
  fill(100);
  ellipse(x,y,50,50)
  x= x+ random(-1,1)
  y= y - 1;
  if (y<0){
    y = height
  }}
  
  background(0,0,0);
  fill(random(0,255),random(0,255),random(0,255))
  rect(200,200,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(0,200,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(0,0,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(200,0,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(400,0,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(600,0,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(0,400,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(0,600,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(600,200,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(600,400,200,200)  
  fill(random(0,255),random(0,255),random(0,255))
  rect(400,200,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(400,400,200,200)
  fill(random(0,255),random(0,255),random(0,255))
  rect(200,400,200,200)
  
  
}
