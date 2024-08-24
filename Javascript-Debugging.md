# Javascript Debugging

## Familiar and common
### console.log, console.info, console.warn, console.error
> 1. console.log: comment out the `console.log()` once you're done debugging, as they can slow down your code
> 2. console.info(): behaves the same way as console.log().

```

let x = 10;
console.log(x);  // Outputs: 10

let x = 10;
let y = 20;
console.log(x, y);  // Outputs: 10 20

let name = 'Alice';
console.log('Hello, %s', name);  // Outputs: Hello, Alice
console.log('Hello ', name); // Outputs: Hello Alice
// console.log() supports string substitution, similar to printf in C.


let obj = {a: 1, b: 2, c: 3};
console.log(obj);  // Outputs: { a: 1, b: 2, c: 3 }
// You can log entire objects, and console.log() will format them nicely.

let arr = [1, 2, 3, 4, 5];
console.log(arr);  // Outputs: [ 1, 2, 3, 4, 5 ] you can log entire arrays.
```


## Not so familiar but useful
## console.table -> display key-values array in table

## console.group

## console.count

## console.time 

## console.trace

## console.assert

## Insert breakpoint by debugger

## Local unit test with keyword -> test, expect
