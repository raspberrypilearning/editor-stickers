<h2 class="c-project-heading--task">Style the new stickers</h2>

Use gradients, shadows, and padding to style your new stickers.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

In **style.css** add styles for `#web` and `#save`. Experiment with the CSS until you are happy with the look.


<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 12
line_highlights: 23-30, 32-39
---
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
--- /code ---
</div>

## Now run your code

Click **Run** to see the styles change.





<div class="c-project-output">

![ADD](images/step6.png)

</div>

Confirm the observable result.
