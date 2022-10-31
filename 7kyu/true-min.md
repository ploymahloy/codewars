DESCRIPTION:

The Math.min function has stopped working, so we have to use our own function. We are off to a good start, but this function doesn't seem to handle everything properly. Add in the proper checks to return NaN for anything that isn't an actual number, except treat null like 0.

Note: This min function need not handle more than two arguments.

```
function min(a, b){
  return (a<b)?a:b;
}
```

SOLUTION:
```
function min(a, b){
  if (a === null && b > 0 || b === null && a > 0) return 0;
  else if (a === null && b === null) return 0;
  else if (a < b) return a;
  else if (b < a) return b;
  else if (a === b) return a;
}
```
