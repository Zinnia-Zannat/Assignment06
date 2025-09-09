
1) var vs let vs const

**var:function scoped, hoisted with default value undefined, allows redeclaration.

**let:block scoped, hoisted but not initialized. Re-assignable,Do not allow redeclaration in the same scope.

**const:block scoped like let, but must be assigned once.Do not allow re-assignable,Do not allow redeclaration in the same scope.
  
     

2) map() vs forEach() vs filter()

**map(): it transform each item and return result in array.

**forEach(): execute a function for each element and return undefined. 

**filter(): it's call when ever the function is truthy and return result in array.

3) Arrow functions (ES6)

**arrow function syntax using (() => {}).return for single expression. 

4) Destructuring assignment (ES6)

**it's use when we need value in a variable from array or object.
const{name,price} = plant;
const[first, ...rest]=arr;

5) Template literals vs string concatenation

**Template literals: use backticks and ${}.
`Hello, ${name}`.

**string concatenation: use backticks and '' for string.
`'Hello ' + name + '!'`.