# Example-3-13-Extension
void setup() {
  size(600,120);
  smooth();
  rectMode(RADIUS);
  ellipseMode(CORNER);
  strokeWeight(12);
  strokeJoin(ROUND);
  rect(75,60,35,35);
  strokeJoin(BEVEL);
  rect(195,60,35,35);
  strokeCap(SQUARE);
  line(270,25,340,95);
  strokeCap(ROUND);
  line(350,25,420,95);
  ellipse(500-35,25,70,70);
}
