### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
```Javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true && availableTime < 20) {
    console.log("I am hungry. I have less than 20 minutes for lunch. Picku up some snacks or your rice with beans plate premade NOW!");
  } else if (hungry === true && availableTime > 30) {
    console.log("I'm  hungry and I have 30 minutes for lunch but today i am freaking out with my tasks.. For now, I can reconsider to eat properly.");
  } else {
    console.log("I am starving! I have between 20 to 30 minutes for lunch.");
  }
};
whatToDoForLunch(true, 5);
console.log("---");

whatToDoForLunch(true, 40);
console.log("---");

whatToDoForLunch(true, 31);
console.log("---");

```