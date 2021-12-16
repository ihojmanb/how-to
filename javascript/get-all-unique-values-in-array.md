```javascript
var array_of_repeated_elements = ['a', 'b', 'a', 'a', 'c', 'b']
var array_of_unique_elements = [...new Set(array_of_repeated_elements)]
console.log(array_of_unique_elements) // returns ['a', 'b', 'c']
```
