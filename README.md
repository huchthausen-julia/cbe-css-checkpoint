# cbe-css-checkpoint
checkpoint web dev foundation

# Bonus Kata: Student Hub Design

You will implement a given [figma design](https://www.figma.com/file/12dwBtznAanXFvboKGiige/Checkpoint-Web-Dev-Foundation).

- [ ] Implement the design with HTML/CSS
- [ ] Use figma to identify colors, fonts, font sizes etc.
  - [ ]  DO NOT use the position information includes in figma
- [ ] Use Google Fonts to load the required fonts
- [ ] Use a `max-width` of `600px` to implement the design (the page and all its content should be centered horizontally in the middle of the viewport)
  - [ ] The design should behave like the [student hub](https://student-hub.coding-bootcamps.eu)
- [ ] Skip parts of the design that you cannot implement or implement them in a possible way
- [ ] Use Bootcamp (svg) icons from https://icons.getbootstrap.com/

## Figma

Quick commands for Figma

- You can zoom when holding the CMD or STRG key and using the mouse wheel
- Press `h` to use the `hand` which allows you to manually move the design
- Press `v` to use the `pointer` which allows you to select single elements of the design
  - The details of selected elements will be shown after you select it 


## Hints

The edge of the header can be realized with a svg mask. An example can be found on [krautipsum](http://krautipsum.com).

The `<select>` element is used to create a selection element. The select element has a default style and can be customized.

```html
<select>
  <option>November Class</option>
  <option>Dezember Class</option>
</select>
```
