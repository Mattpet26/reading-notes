# Objects

- When we store things in an object, we access the values using the keys with object access notation.

- The [] after an object or array are called **object access notation** when used to retrieve a value.

- A key value pair is also known as a **property**.

- **Dot notation** can help us not have to use [].
  - console.log('dot notation :' obj.key)
  - console.log('access notation:' obj['key'])

# Everything in Javascript is an object

- var obj = {
  - key : 'Value',
  - cool : true,
  - 'Key line' : 3.14,
  - 'Number' : 99,
- }

// key : value,

# Methods

- Methods are functions that live in objects.

- To call a method, we must call the variable name with the function key. So obj2.talk

- var obj2 = {
  - name : 'Kayne',
  - talk : function(){
    - console.log('Bark, Bark');
  - }
- }
- obj2.talk();

# Changing object values

var x = 2;
console.log(x);
x = 3;
console.log(x); // value is now 3

## This

- This refers to the local var, which only works as long as we are within that var.

var scooby = {
  name : 'Scooby';
  favSnack : 'Scooby-snack',
  color : 'brown',
  intro : Function(){
    console.log('I am ' + **this**.name + 'can I have a ' + **this**.favSnack + '?')
  }
}
scooby.intro();



[Click here](README.md)