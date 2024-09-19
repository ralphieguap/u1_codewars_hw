## Return Negative

```js
function makeNegative(num) {
  if(num <= 0) return num;
  return num * -1;
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
        sum += arr[i];
         }
  }
  return sum;
```

```js
function square(num) {
    return num * num;
}
```

## Sum Arrays

```js
// Sum Numbers
function sum(numbers) {
    "use strict";
    
    // Return 0 if the array is empty
    if (numbers.length === 0) {
        return 0;
    }

    // Initialize the sum variable
    let total = 0;

    // Loop through each number in the array
    for (let i = 0; i < numbers.length; i++) {
        total += numbers[i]; // Add the current number to the total
    }

    return total; // Return the total sum
}
```

## Reversed Strings

```js
function solution(str) {
    return str.split('').reverse().join('');
}
```

