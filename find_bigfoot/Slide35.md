<<One column text>>

Next, back to our html file. We need to make it so that whenever we win the game and find Bigfoot, the moveBigFoot function will be called and it’ll move him to a new location based on the two numbers we just generated.

Let’s create a new onclick method in our `` tag in the html file.

```html
<img id="bigFoot" onclick='alert'('Woohoo, you win! You found Bigfoot!')
	onclick = "moveBigFoot()";
/>
```

Now let’s try and run that and see if it works.

Did it?

No?

Okay. Let's see what we can do about that.