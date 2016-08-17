<h2>ES6: Arrow functions</h2>

```javascript

// ES5

var numbers = [3,5,6,8];

var double = numbers.map(function(number) {
                return number * 2;
            });

//ES6

var numbers = [3,5,6,8];

var double = numbers.map(number => number * 2);

// **
```
