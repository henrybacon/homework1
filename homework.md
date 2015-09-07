puzzle 1

down();
down();
down();
down();
down();
down();
down();
right();
right();
right();
right();
up();
up();
right();
right();
right();
right();

puzzle 2:

function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}

move(down,6);
move(right,3);
move(up,2);
move(right,2);
move(down,3);

puzzle 3:

function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}

move(down,2);
var color = getColor();
move(right,2);
move(down,3);
setColor(color);
move(right,2);
move(up,1);

puzzle 4:

function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}

move(down,4);
move(right,1);
var color = getColor();
move(down,1);
setColor(color);
move(right,3);
move(up,1);
var color = getColor();
move(down,1);
setColor(color);
move(right,2);

puzzle 5:

function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}

function decide() {
if (getColor() == "blue") {
  down();
} else {
  up();
} 
}


move(right,2);
decide();
move(right,2);
decide();
move(right,2);
decide();
move(right,3);


puzzle 6

function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}

function decide2() {
  var initial = getColor();
 	if (initial == "blue") {
  down();
  down();
  down();
  }
    if (getColor() == "blue") {
    right();
    down();
} else {
  up();
  up();
  up();
  if (getColor() == "blue") {
    right();
    up();
  }
    
  
} 
}


move(right,1);
decide2();

puzzle 7:

function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}

function runDown() {
  while (getColor() != "red") {
    down();
  }
}

function runUp() {
  while (getColor() != "red") {
    up();
  }
}

runDown();
move(right,2);
runUp();
move(right,2);
runDown();
move(right,2);
runUp();
move(right,2);
runDown();
right();

puzzle 8:
function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}


function downSolve(total) {
  var count = 0;
  while (count < total) {
    down();
    count = count + 1;
  }
}

function upSolve(total) {
  var count = 0;
  while (count < total) {
    up();
    count = count + 1;
  }
}

downSolve(8);
move(right,2);
upSolve(7);
move(right,2);
downSolve(7);
move(right,2);
upSolve(7);
move(right,2);
downSolve(7);
move(right,1);


function move(direction,total) {
  var count = 0;
  while (count < total) {
    direction();
    count = count + 1;
  }
}

puzzle 10:

down();
var color1 = getColor();
down();
var color2 = getColor();
down();
var color3 = getColor();
down();
var color4 = getColor();
down();
var color5 = getColor();
down();
var color6 = getColor();
down();
var color7 = getColor();
down();
var color8 = getColor();
down();
right();
setColor(color1);
right();
up();
setColor(color2);
right();
up();
setColor(color3);
right();
up();
setColor(color4);
right();
up();
setColor(color5);
right();
up();
setColor(color6);
right();
up();
setColor(color7);
right();
up();
setColor(color8);
right();
up();
up();






