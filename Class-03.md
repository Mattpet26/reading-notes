# HTML lists and Control Flow with JS

**Lists**
- There are three types of HTML lists
  - Ordered - These lists use numbers.
  - Unordered - This list uses bullets
  - Definition - These are used to define terminology

**Boxes**
- CSS can be used to control the dimensions, borders, ect. of a box
- Boxes have three main properties: Margin, border and padding

**Decisions and Loops**
- Conditional statements allow code to make decisions about what to do next.

# Logical Operators
- Short circuit logic, they do not convert to true or false, they STOP at the first value that meets their condition.

- **logical or** || stops at the first truthy thing. Otherwise it ends on the last thing.

- **logical and** && short circuits on the first false thing. Otherwise end on the last thing.

- **not operator** ! turns a truthy thing into false or a falsey thing into true.

- **falsey things:**
 - 0;           //number
 - undefined;  //undefined
 - null;
 - NaN;      //number
 - '';      //string
 - False;  //boolean

# Control Flow
- Idea of directing the way your app flows other than reading every line once top to bottom.

- **For loops** the thing in them can repeat a set amount of times. They have syntax. 
  - for('Variable declaration, condition, iterator,)
  - iteration is i++

- console.log('I happened 1 time')
  - Make the loop happen once to test it, then paste into the for loop. The loop runs 10 times.

- for(var i=0; i <10; i++){
  - x = x + 1
  - consol.log('I happened ' + x + ' time')
  - }

-**While loops** this loop will repeat until the condition is met.
  - 

var countdown = 99;

while(countdown > 0){
  console.log(countdown + 'bottles of water on the wall');
  console.log(countdown + 'bottles of water');
  console.log('take one down, pass it around');
  countdown --;    //this takes one away per run
  console.log(countdown + 'bottles of water on the wall');
}

-**Do while loop** this loop is useful to ask a question.


var yesOrno = prompt('Am i cool?')

while (yesOrno === 'no'){
  yesOrno = prompt('Am I cool? - you were wrong, please try again');
}

do {
  var lovesDogs = prompt('Do I love dogs?');
} while(lovesDogs.toLowerCase !== 'yes');


# Arrays
- An array is a container for more than one thing. In concept they are similar to an unordered list. We should try to keep similar contents in arrays.

var potatoArray = ['russet', 'golden', 'yukon'];
potato array[0] === 'russet';
potato array[0];

potato array[1] === 'golden';
potato array[1];

potato array[2] === 'yukon';
potato array[2];

var aPotatoLiked = prompt('Which potato do i like?');

if(aPotatoLiked === potatoArray[0]) || aPotatoLiked ===poatoArray[1]){
  console.log('yes')
}

for(var index = 0; index < 3; i++){
  console.log('index :', index);
  console.log('potatoArray[index]', potatoArray[index]);
}


[Click here](README.md)