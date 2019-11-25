# javascript-exercises

1. getFirst

Write a JavaScript function to get the first element of an array. Passing a parameter 'n' will return the first 'n' elements of the array.

```
Test Data : 
console.log(getFirst([7, 9, 0, -2])); 
console.log(getFirst([],3));
console.log(getFirst([7, 9, 0, -2],3));
console.log(getFirst([7, 9, 0, -2],6));
console.log(getFirst([7, 9, 0, -2],-3));
Expected Output : 
7
[] 
[7, 9, 0] 
[7, 9, 0, -2] 
[] 
```

2. getArrayItems

Write a JavaScript function to get the element of an array. Passing a parameter 'n' will return the first 'n' elements of the array. Passing a parameter 'first/last', will items from the beggining or the end (beginning is default)
[Advanced: Make the function flexible to be able to take the arguments in any order]

```
Test Data : 
console.log(get([7, 9, 0, -2])); 
console.log(get([],3));
console.log(get([7, 9, 0, -2],3));
console.log(get([7, 9, 0, -2],6));
console.log(get([7, 9, 0, -2],-3));
Expected Output : 
7
[] 
[7, 9, 0] 
[7, 9, 0, -2] 
[] 

Test Data : 
console.log(get([7, 9, 0, -2],1,last)); 
console.log(get([7, 9, 0, -2],3),last); 
console.log(get([7, 9, 0, -2],6),last);
Expected Output : 
-2 
[9, 0, -2] 
[7, 9, 0, -2]
```
