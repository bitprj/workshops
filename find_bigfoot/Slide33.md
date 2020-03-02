<<One column text>>

So since we have two numbers to generate (for `left:` and `top:`) we need to create two new variables for those values.

```javascript
function moveBigFoot() {
  var picture = document.getElementById('bigFoot')

  var x = Math.random() * 300
  var y = Math.random() * 300
}
```

This will generate two random numbers between 0-300 whenever the function is run.

