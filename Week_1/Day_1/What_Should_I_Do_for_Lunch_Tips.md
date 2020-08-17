### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true) {
    if (availableTime < 20) {
      console.log("Pick up something nearyby and eat back in the lab.");
    } else if (availableTime >= 20 && availableTime < 30) {
      console.log("Let's try a place nearby");
    } else {
      console.log("Are you sure all the work is done?");
    }
  } else {
    console.log("Please go back to work.");
  }
};
```
