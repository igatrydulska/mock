let img;
let img1;

function preLoad() {

}

function setup() {
  createCanvas(1000, 600);
  background(0) //I want my background to be black to contrast blue
  img = loadImage('niebo.jpg');
  img1 = loadImage('niebo2.jpg');

}

//drawing a line which will separate "present time" from "future"

function preLoad () {


}

function draw() {
  push(); //inserting the picture
    background(220);
    image(img, 0, 0, 500, 500);
  pop();  

  push(); //creating the button
    let button;
    button = createButton('yes');
    button.position(480,500);
    button.mousePressed(image(img1,500,0,500,500));
  pop();




  //push();
    //stroke(250);
    //strokeWeight(1);
    //line(250,0,250,500);

    //creating both labels; "future" will rotate faster than "present" to show that the climate change will accelerate
    //fill(0,0,255);
    //textSize(30);
    
    //rotateX((millis()) / 1000);

    //text('present', 75, 50);

   // fill(0)
    //text('future', 350, 50);
  pop();

}

let counter = 0;
let step = 150;
let x = step/2;
let y = step/2;


//map colour values to be blue 
//make the colour values correspond to the live table
//create another half 
//create a button which will show the future 

