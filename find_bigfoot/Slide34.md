<<One column text>>

Now that we have our two numbers, we have to actually make them apply to our picture variable. Here, we’ll use the style left and style top property.

```javascript
function moveBigFoot() {
  var picture = document.getElementById('bigFoot')

  var x = Math.random() * 300
  var y = Math.random() * 300

  picture.style.top = x + 'px'
  picture.style.left = y + 'px'
  }
}
```

This will take any images that follow the parameters of the picture variable (which is just finding the `id` `bigFoot`) and set the top and left position to the random numbers that it generates.

