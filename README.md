#Road to learning ES6 
 ES6 syntax and short description to understand it

### Block scoping
#### Issue
 Declaration hoisting in javascript create confusion for new developer and also creates bug in application.
 
#### ES6
 
 `let` Keyword allow to declare variable in block scope.
```javascript
var count = 30;
if (true) {
    let count = 40;
    // here count value will be 40.
}
// here count value will be 30.
```
### Constant declaration

`const` keyword allow to declare variable which can not be modify after declaration so const variable must be initialized on declaration.
it is block scope same as `let`.



