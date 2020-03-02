<<One column text>>

It looks like having two onclick methods is confusing the program. It will make it a lot easier and more efficient to move the alert to the moveBigFoot() function, so that it will all happen at once. Let’s take out the `alert` in the `img` tag and put it in our moveBigFoot() function

So now, our new ``in the html file should just look like this

```html
<img id="bigFoot" onclick = "moveBigFoot()"; />
```

And our `moveBigFoot()` function in scripts.js should look like this

```javascript
function moveBigFoot() {
  alert('Woohoo, you win! You found Bigfoot!')
  var picture = document.getElementById('bigFoot')

  var x = Math.random() * 300
  var y = Math.random() * 300

  picture.style.top = x + 'px'
  picture.style.left = y + 'px'
}
```