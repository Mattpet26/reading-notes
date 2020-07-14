# Constructors

- **New** is a keyword used exclusively to call constructor functions.

- function Studnet(car, color, drink, home){
  - this.favCar = car;
  - this.favColor = color;
  - this.favDrink = drink;
  - this.homeTown = home;
  - this.cool = true;
  - this.class = 201d65;
  - this.student = true;
  - this.teacher = 'Nicholas';
  - this.greeting = function {
    - console.log('Sup')
  - }
- } 
- var jack = new Student('volvo', 'red', 'soda', 'CA');

## Factory Function
- Placing an object into a function. Now we can call the function and give it parameters instead of typing it all out.

- function makeStudnet(car, color, drink, home){
- var student = {
  - favCar: car,
  - favColor: color,
  - favDrink: drink,
  - homeTown: home,
  - cool: true,
  - class: 201d65,
  - student: true,
  - teacher: 'Nicholas',
  - greeting: function {
    - console.log('Sup')
  - }
- }; 
- return student;
- }

- var matthew = makeStudnet('BMW I8', 'blue', 'Tea', 'WI')













[Click here](README.md)