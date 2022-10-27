DESCRIPTION:

Functional closures can get overly attached. Set them straight!

Why doesn't greet_abe() actually greet Abe?

SOLUTION:
```
var greet_abe = function(name) {
var name = 'Abe';
  return ("Hello, " + name + '!');
};
var greet_ben = function(name) {
name = 'Ben';
  return ("Hello, " + name + '!');
};
```
