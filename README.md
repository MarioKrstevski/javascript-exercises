# javascript-exercises


## 1. getArrayItems

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

## 2. separateEven

Write a JavaScript program which accept a number as input and insert dashes (-) between each two even numbers. 

Write a JavaScript function to get the first element of an array. Passing a parameter 'n' will return the first 'n' elements of the array.

```
For example if you accept 025468 the output should be 
Expected Output : 
0-254-6-8.
```


## 3. arraySort

Write two functions that would be extended on the array prototype, sortAsc() & sortDesc(), that would sort an array by ascending and descending respectfully, they should work both on number and string values

```
Sample array : var arr1 = [ 3, 8, 7, 6, 5, -4, 3, 2, 1 ];
                    arr1.sortAsc()
Sample Output : -4,-3,1,2,3,5,6,7,8
```
// new comment

## 4. mostFrequentItem

Write a JavaScript program to find the most frequent item of an array.

```

Sample array : var arr1=[3, 'a', 'a', 'a', 2, 3, 'a', 3, 'a', 2, 4, 9, 3];
Sample Output : a ( 5 times ) 
```


## 5. mostFrequentWord

Write a JavaScript program to find the most frequent word in a sentance or paragraph. If there are multiple with the same occurence, return the first one.

[Advanced: Make the function accept a second parameter that would ignor the common words such as 'the' and 'and']

```
Sample array : var string = "Today is Monday the most beautiful day in the world, where things are always splendid and hopeful"
Sample Output : "the"
```


## 6. swapCase
Write a JavaScript program which accept a string as input and swap the case of each character. 

```
For example if you input 'The Quick Brown Fox'
Expected Output : 'tHE qUICK bROWN fOX'.
```

## 7. sum

Extend the array prototype with a new function sum() that will sum all the items in the array and return it as the last element,
also create a function sum() that takes an array of integers and returns the sum

```
v1:
For example if you accept sum([1,2,3,4,5,6])
Expected Output : 21


v2: 
For example if you accept [1,2,3,4,5,6].sum()
Expected Output : [1,2,3,4,5,6,21]
```

## 8. binarySearch

Write a JavaScript program to perform a binary search.

Note : A binary search or half-interval search algorithm finds the position of a specified input value within an array sorted by key value.
```
Sample array : 
var items = [1, 2, 3, 4, 5, 7, 8, 9];
Expected Output : 
console.log(binary_Search(items, 1)); //0 
console.log(binary_Search(items, 5)); //4
```


## 9. sumPositions

There are two arrays with individual values, write a JavaScript program to compute the sum of each individual index value from the given arrays.

```
Sample array : 
array1 = [1,0,2,3,4];
array2 = [3,5,6,7,8,13];
Expected Output : 
[4, 5, 8, 10, 12, 13] 
```
## 10. removeDuplicates


Write a JavaScript program to find duplicate values in a JavaScript array.

```
For example if you accept ['2',2,'mario','hi','there','mario']
Expected Output : 
['2',2,'mario','hi','there']
```


## 11. flattenArray

Write a JavaScript program to flatten a nested (any depth) array. If you pass another argument (shallow) as true, the array will only be flattened a single level.

Sample Data : flatten([1, [2], [3, [[4]]],[5,6]]); 
Output: [1, 2, 3, 4, 5, 6]

//with shallow = true
flatten([1, [2], [3, [[4]]],[5,6]], true); 
Output: [1, 2, 3, [[4]], 5, 6]


## 12. union

Write a JavaScript program to compute the union of two arrays. Sample Data :
```
console.log(union([1, 2, 3], [100, 2, 1, 10]));
[1, 2, 3, 10, 100]
```

## 13. removeFalsy
Write a JavaScript function to remove. 'null', '0', '""', 'false', 'undefined' and 'NaN' values from an array.

```
Sample array : [NaN, 0, 15, false, -22, '',undefined, 47, null]
Expected result : [15, -22, 47]
```

## 14. findDifferences
Write a JavaScript function to find the difference of two arrays.

```
Test Data :
console.log(difference([1, 2, 3], [100, 2, 1, 10])); 
["3", "10", "100"]
console.log(difference([1, 2, 3, 4, 5], [1, [2], [3, [[4]]],[5,6]])); 
["6"]
console.log(difference([1, 2, 3], [100, 2, 1, 10]));
["3", "10", "100"] 
```
## 15. findPairSum

Write a JavaScript program to find a pair of elements (indices of the two numbers) from an given array whose sum equals a specific target number.

```
Input: numbers= [10,20,10,40,50,60,70], target=50
Output: 3, 4
```
## 16. findIsTotalPossible [Advanced]

Write a JavaScript program to find if numbers from an given array sum can be equal a specific target number.

(It doesn't have to be 2 as the previous example, it can be all of them together to form the sum . )
Write a JavaScript program to find if numbers from an given array sum can be equal a specific target number. a+b+c = target)

// Look into dynamic programming, 
// Implement it further, if there are multple combinations for the same total, choose the one with less numbers included 
// knapsack problem

```
Input: numbers= [10,20,10,40,50,60,70], target=55
Output: false

Input: numbers= [10,20,10,40,50,60,70], target=40
Output: 10+20+10
Output: 40
```
## 17. getRandom

Write a JavaScript function to get a random item from an array.

## 18. moveElement

Write a JavaScript function to move an array element from one position to another.

```
Test Data :
console.log(move([10, 20, 30, 40, 50], 0, 2));
[20, 30, 10, 40, 50]
console.log(move([10, 20, 30, 40, 50], -1, -2));
[10, 20, 30, 50, 40]
```

## 19. generateArrayLength

Write a JavaScript function to generate an array of specified length, filled with integer numbers, increase by one from starting position.

Test Data :
console.log(array_range(1, 4)); 
[1, 2, 3, 4]
console.log(array_range(-6, 4));
[-6, -5, -4, -3]

## 20. generateArraySteps

Write a JavaScript function to generate an array between two integers of 1 'step' length if step value is not provided, otherwise step by the 'step' value

Test Data :
console.log(rangeBetwee(4, 7)); 
[4, 5, 6, 7]
console.log(rangeBetwee(-4, 7));
[-4, -3, -2, -1, 0, 1, 2, 3, 4, 5, 6, 7]

console.log(rangeBetwee(-4, 7,3));
[-4, -1, 2, 5]

[Advanced] Extend the function to work with Characters

console.log(num_string_range('a', "z", 2));
["a", "c", "e", "g", "i", "k", "m", "o", "q", "s", "u", "w", "y"]
