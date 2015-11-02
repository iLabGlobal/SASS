# SASS
This is the location of all the code we have used in class.


Code from Monday October 26, 2015
Copy and paste below this line
//EXAMPLE #1
//setting the paramenter
//printing to concole(bottom of Processing window)

float y = 0.0;`

void draw() {
    frameRate(120);
  background(204);
  line(0, y, 100, y);
  y = y + 0.5;
  if (y > height) {
//    y = 0.0; 
//noLoop();
  }
  println(y);  // Print value of y to the console
}


//EXAMPLE #2
/*This an example of the height 
of the line changing as the size of the canvas changes*/


//size (600, 200);
int a = 8;
int b = 10;
line(a, 0, a, height);
line(b, 0, b, height);
strokeWeight(4);
line(a/b, 0, a/b, height);
  
