
<h2 class="c-project-heading--task">Style the text</h2>

--- task ---

Use CSS to style the text for your sticker.

--- /task ---


--- task ---

Click on the file icon, and the `style.css` file.

![screenshot](images/css-file.png)

--- /task ---


--- task ---

Add the CSS code below to style the text that uses the id `coding`.

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

An `id` is added to HTML, and used in the CSS so the styles are changed in the right place.

</div>


--- task ---

Experiment with the font. You could try changing the `font-family` to: 
- `Impact`
- `Comic Sans MS`
- `Trebuchet MS`. 

You can also change the font-weight and the font-size.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 5
line_highlights: 11-17
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
}
--- /code ---
</div>
--- task ---

**Run** your code. See how it has changed the style.

--- /task ---




<div class="c-project-output">

![ADD](images/step3.png)

</div>
