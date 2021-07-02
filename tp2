PFont miLetra;
PImage Superheroes1;
PImage Superheroes2;
PImage Superheroes3;
float posxescudo;
float posxthor;
float posxvision;

void setup (){
  size (700,700);
  textAlign (CENTER, CENTER);
  imageMode (CENTER);
  posxescudo = 574;
  posxthor = 100;
  posxvision = 340;
  
  //cargo de tipografía e imágenes
  miLetra = loadFont ("marvelstudios.vlw");
  Superheroes1 = loadImage ("escudo_marvel.png");
  Superheroes2 = loadImage ("thor_marvel.png");
  Superheroes3 = loadImage ("vision_marvel.png");
  }
  
  void draw (){
    background (255,0,0);
    textSize (frameCount);
    //textoFont ( miLetra );
    text ( "MARVEL STUDIOS", width/2, height/2 );
    image ( Superheroes1, posxescudo, 574, 300, 300);
    image ( Superheroes2, posxthor, 750);
    image ( Superheroes3, posxvision, 210);
    posxescudo = posxescudo + 0.5;
    posxthor = posxthor - 0.5;
    posxvision = posxvision +1;
    }
