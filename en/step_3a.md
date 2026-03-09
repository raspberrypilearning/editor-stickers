<h2 class="c-project-heading--task">Style the background</h2>

--- task ---

Add to how the sticker looks with a gradient background and padding.

--- /task ---


--- task ---

Add the to the CSS with the code below.

--- /task ---


--- task ---

Try replacing `red` and `magenta` with other options. You can find more CSS colour names [here](http://jumpto.cc/colours){:target="_blank"}.

--- /task ---

--- task ---

Experiment with `padding` and `border-radius` to change how the sticker looks.

--- /task ---


<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 12
line_highlights:
---
.sticker {
  display: inline-block;
  vertical-align: top;
  margin: 5px;
}

#coding {
  font-size: 40px;
  font-weight: bold;
  color: black;
  font-family: "Courier New";
  text-align: center;
  background: linear-gradient(red, magenta);
  padding: 50px 30px;
  border-radius: 20px;
}
--- /code ---

--- task ---

**Run** your code. See how it has changed the style.

--- /task ---
</div>
