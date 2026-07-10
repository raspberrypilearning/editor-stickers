## Style the new stickers

Use gradients, shadows, and padding to style your new stickers.

In **style.css** add styles for `#web` and `#save`. Experiment with the CSS until you are happy with the look.

```css filename="style.css" line_numbers="true" line_number_start="12" line_highlights="23-30,32-39"
#coding {
  font-size: 40px;
  font-weight: bold;
  color: black;
  font-family: Courier New;
  background: linear-gradient(red, magenta);
  padding: 50px 30px;
  border-radius: 20px;
  text-align: center;
}

#web {
  font-size: 40px;
  font-family: Impact;
  text-shadow: 2px 2px grey;
  background: radial-gradient(yellow, orange, red);
  padding: 30px;
  border-radius: 100px;
}

#save {
  font-size: 40px;
  color: white;
  background: linear-gradient(green, yellow, orange, red, purple, blue);
  padding: 30px;
  border-radius: 5px;
  text-align: center;
}
```

## Now run your code

Click **Run** and check that the sticker styles change on the page.

![ADD](images/step6.png)
