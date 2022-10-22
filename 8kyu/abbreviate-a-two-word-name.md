DESCRIPTION:

Write a function to convert a name into initials. This kata strictly takes two words with one space in between them.

The output should be two capital letters with a dot separating them.

It should look like this:

Sam Harris => S.H

patrick feeney => P.F

SOLUTION:
```
function abbrevName(name){
  let wholeName = name.split(' ');
  
  let firstName = wholeName[0];
  let lastName  = wholeName[1];
  
  let firstInitial = firstName[0];
  let lastInitial  = lastName[0]
  
  return (firstInitial.toUpperCase() + '.' + lastInitial.toUpperCase());
}
```
