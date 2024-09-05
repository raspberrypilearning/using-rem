Where possible, `rem` should be used to state the size of an element in a HTML webpage. 

This is because `rem` works with the default size that the user's browser has specified. `1rem` is typically equivalent to 16px but a user might decide to set their `rem` to a larger or smaller size based on their needs and preferences. 

When you use `3rem` for the size, you are stating that the element is three times the size of the default size. 

--- code ---
---
language: CSS
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 2
---
.bigfont {
  font-size: 3rem;
}
--- /code ---

Using `rem` is great because it allows your webpage to be responsive to the needs of your user. 
