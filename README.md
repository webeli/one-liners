# JavaScript One-Liners

##### Generate a random string
```javascript
// This simply generates a random float,
// casts it into a String using base 36 and remove the 2 first chars 0 and .
Math.random().toString(36).substr(2);
```
