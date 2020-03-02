<<One column text>>

Open your script.js file and let’s make a new function `moveBigFoot();`

```javascript
function moveBigFoot() {}
```

Now remember, we’re trying to move bigfoot randomly around the screen. So the first thing we need to do is make a variable that will get our image. Like earlier, we’ll use “document.getElementbyId.”

```javascript
function moveBigFoot() {
  var picture = document.getElementById('bigFoot')
}
```

This will help us out later on.

