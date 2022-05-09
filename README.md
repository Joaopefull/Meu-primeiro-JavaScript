# Meu-primeiro-JavaScript
JavaScript mini games by code.org
*/
for (var count = 0; count < 4; count++) {
  moveForward();
}
turnLeft();
for (var count2 = 0; count2 < 4; count2++) {
  moveForward();
}
turnLeft();
moveForward();
moveForward();
turnRight();
moveForward();
*/
turnLeft();
destroyBlock();
moveForward();
destroyBlock();
moveForward();
placeTorch();
turnRight();
for (var count = 0; count < 3; count++) {
  moveForward();
}
destroyBlock();
moveForward();
turnRight();
placeTorch();
for (var count2 = 0; count2 < 2; count2++) {
  moveForward();
  destroyBlock();
}
*/
moveForward();
placeBlockAhead("cobblestone");
moveForward();
for (var count = 0; count < 2; count++) {
  moveForward();
  destroyBlock();
}
*/
for (var count = 0; count < 7; count++) {
  destroyBlock();
  ifLavaAhead(function() {
    placeBlockAhead("cobblestone");
  });
  moveForward();
}
*/
turnLeft();
ifLavaAhead(function() {
  placeBlockAhead("cobblestone");
});
moveForward();
ifLavaAhead(function() {
  placeBlockAhead("cobblestone");
});
moveForward();
destroyBlock();
moveForward();
destroyBlock();
moveForward();
turnRight();
destroyBlock();
for (var count = 0; count < 3; count++) {
  ifLavaAhead(function() {
    placeBlockAhead("cobblestone");
  });
  moveForward();
  destroyBlock();
}
turnLeft();
ifLavaAhead(function() {
  placeBlockAhead("cobblestone");
});
*/
turnRight();
for (var count = 0; count < 6; count++) {
  placeBlock("rail");
  moveForward();
}
turnRight();
for (var count2 = 0; count2 < 6; count2++) {
  placeBlock("rail");
  moveForward();
}

turnLeft();
for (var count = 0; count < 2; count++) {
  moveForward();
}
destroyBlock();
moveForward();
destroyBlock();
moveForward();
ifBlockAhead("", function() {
  placeBlockAhead("bedrock");
});
moveForward();
moveForward();
turnLeft();
for (var count2 = 0; count2 < 5; count2++) {
  moveForward();
}
turnRight();
shear();
turnLeft();
