
<h2 class="c-project-heading--task">Challenges</h2> 

--- task ---

Make more stickers using different gradient directions and adding images and text and using borders and outlines. 

--- /task ---


--- task ---

### Change the gradient direction

Edit your gradients to run in different directions. 

You can use `to` to change the direction. For example: `to top`, `to left`, or `to right`. For a diagonal gradient you give two directions. This example uses `to bottom left`.

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: false
---

background: linear-gradient(to bottom left, white, yellow, tomato);

--- /code ---
</div>

--- /task ---


--- task ---

### Make outlines

This uses `outline` to create another border outside the usual one. 
`outline-offset` gives the gap between the border and the outline. 

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: false
---
outline: 4px solid tomato;
outline-offset: 2px;

--- /code ---
</div>


--- /task ---


--- task ---

### Rotate 

Rotate text or images by using `transform: rotate` in your CSS.

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: false
---
transform: rotate(-15deg);
--- /code ---
</div>

--- /task ---



![A group of five colourful digital stickers.](images/stickers-finished.png)


