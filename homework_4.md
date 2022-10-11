# Fourth written homeworkd - w11d03
## Big O Notation
Big O notation is a way to describe how many cycles a algorithm runs in terms of the size of the entry 'N'.

## Omega, Theta and Big O
Omega refers to the best case scenario for the algorithms run time. Theta is the average time the algorithm will take. If looping through a array to find a item, Omega would be finding the item in the first index of the array, and theta would be finding the item in the middle of the array.

Big O is the worst case scenario, and the longest time it can take for the algoeithm to complete. In mamy cases, theta and big O are the same.

## Linear time complexity O(N)

Linear time complexity is found in an algorithm that looks for a value in a array, such as 
```js
function findRandomNumberInArray(arr) {
  const randomNum = Math.floor(Math.random() * arr.length)
  for (let i = 0; i < arr.length; i++) {
    if (randomNum === arr[i]) return arr[i]
  }
}
```
## Quadratic time complexity

Quadratic time complexity can happen with nested loops, such as
```js
   for (let i = 0; i < array.length; i++){
       for (let j = 0; j < array.length; j++){
           if (i !==j && array[i] === array[j]){
               return `Repeat values at ${i} and ${j}`;
           }
       }
   }
```
