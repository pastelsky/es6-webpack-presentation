<h2>ES6: Template literals</h2>

```javascript
// ES5
var a = "Hello " + name + " visitor number " + visitor 
      + "! You have " + money + " in your account!"

// ES6
const a = `Hello ${name} visitor number ${visitor}! 
           You have ${money} in your account!`

// multiline strings
const email = ` Dear ${name},

  Hope you're doing ${yourMood}. I am doing ${myMood}.

Your's ${salutation}
  ${whoami}`
```
