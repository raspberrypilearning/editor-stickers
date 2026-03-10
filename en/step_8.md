<h2 class="c-project-heading--task">Style the image sticker</h2>


--- task ---

In **style.css** add styles for `#purplerobot`. Add backgrounds and rounded corners behind your robot images.

--- /task ---


<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 32
line_highlights: 41-45
---
#save {
  font-size: 40px;
  color: white;
  background: linear-gradient(green, yellow, orange, red, purple, blue);
  padding: 30px;
  border-radius: 5px;
  text-align: center;
}

#purplerobot {
  background: radial-gradient(gray, purple);
  padding: 20px;
  border-radius: 150px;
}
--- /code ---
--- task ---

**Test:** Click **Run** to see the styles change.

--- /task ---
</div>


<div class="c-project-output">

![ADD](images/step7.png)
</div>
