### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
fconst whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true && availableTime < 20) {
    console.log("pick up a snack or grab something you have ready at home.");
  } else if (hungry === true && availableTime >= 20 && availableTime < 30) {
    console.log("you deserve a break and should take time to cook a tasty meal.");
  } else if (hungry === true && availableTime > 30) {
    console.log("this is an intense program after all and you should probably reconsider.");
  } else if (hungry === false) {
    console.log("get back to work");
  }
};
```