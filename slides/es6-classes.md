<h2>ES6: Classes</h2>
```

// ES5 
var Car = function(name) { this.name = name }

Car.prototype.printName = function() { console.log('this.name') }

// ES6 
class Car {
  constructor(name) {
    this.name = name;
  }

  printName() { console.log('this.name'); }
}
```
