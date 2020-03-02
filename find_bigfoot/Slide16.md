<<One column text>>

Here's what went wrong. We expected the quotation mark after `alert(` to indicate the beginning of the message, but what it actually did was indicate the end of the `onclick` attribute.

Here's a little trick you can use to fix that. In JavaScript, you can use either `"` or `'` around text (the technical term is a [**string**](http://www.w3schools.com/js/js_strings.asp)). So change the inner quotes to single quotes, like this:

```html
onclick="alert('Woohoo, you win! You found Bigfoot!');"
```

