PShape myShape;

void setup() {
  size(600,600);
  frameRate(60);
  myShape = loadShape("shape.svg");
  
  background(255);
  shape(myShape, 10, 10, 300, 300);
}
void draw() {
}
