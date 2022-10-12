<h1>Fourth Written Homework W12D01</h1>
<h2>What is Big O Notation? Contrast Big O with Omega and Theta. Show 1 Code Example Each Of Linear Time Complexity and Quadratic Time Complexity.</h2>

Big O notation is the language and metric used to describe the efficiency of algorithms and how one algorithm solves big problems compared to another.

The Constrast between Omega and Theta is Omega is the best possible result one can expect from an algorithm at runtime well as Theta is the expected case or averaged result one can expect.

There are 7 Big O Notations

O(1)
The input to the algorithm does not matter - the algorithm will still take the same amount of time to run
```js
const arr = [1,2,3,4,5]
console.log(arr[2])
```

O(N)
As the size of the input grows the processing time required by the algorithm will grow at the same pace.
```js
const arr = [1,2,3,4,5]
for (let i = 0; i < arr.length; i++){
    if(arr[i] === 2){
        return i
    }
}
```

O(N^2)
For each time the input grows the processing time required by the algorithm will grow exponentially
```js
const arr = [1,2,3,4,5]
for (let i = 0; i < arr.length; i++){
    for (let j = 0; j < arr.length; j++){
        // code block
    }
}

```

O(log N)
For each time the input grows the processing time required by the algorithm will increase by half what it previously increased by.
```js
const n = 16777216

log(n)

function log(n) {
  let j = 0
  
  for(let i = n; i >.999; i /= 2) {
    console.log(
			`The result of iterion ${j} is ${i}`
		)
    j++
  }
}
```

O(N log N)
For each time the input grows the processing time required by the algorithm will grow linealy and logarithmically
```js
for (let i = 0; i <= arr.length; i++){
    for (let j = 0; j < arr.length; j *= 2)
}
```

O(2^N)
For each time the input grows the processing time required by the algorithm will double. 
```js
function fib(num){
    if (num <= 1) return num;
    return fibonacci(num - 2) + fibonacci(num - 1);
}
```

O(N!)
Occurs when every possible solution to a problem may have to be calculated for the correct output to be determined.
```js
// Travelling Salesman problem
```
