<<One column text>>

We should also go ahead and add the `onload` attribute to the body tag. There are a couple more things we have to do. First, go ahead and get rid of `src` tag, as we will be adding that with the function. Then, add an `id` to the `img` tag. This is so we can change the `src` attribute after the page loads.

```html
<body onload="loadBigFoot()">
  <img id="bigFoot" onclick="alert('Woohoo, you win! You found Bigfoot!');" />
</body>
```

