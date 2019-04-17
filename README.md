Fix me! - Execercise
====================

#part 1

- h3 was a SECOND child, first child is text node (white space)!! so: childnodes[1]
- event needed here was 'keyup'

#part 2

- keyup events on all inputboxes. in the handler function I used the keyword :
'event' for looking which key is pressed (must be enter) (event.keyCode === 13)
- function addRow for adding rows and adding remove button
- funciton deleteRow for deleting the row if remove button is clicked

#part 3

- difficult to have all 4 elements in the list using for loop
- when you go away from the input : event: focusout

#part 4

- searching with innerText of eacht <tr>, and indexOf
- difficult to place checkbox to right and vertically centered
- WHOLE column disappears
- color gray and white of table are not ok at first when removing columns
- highlighting the found text: I didn't do this ...

#part 5

- nested setTimeouts and functioncalls in functions
- used css transitions

#part 6

- position relative
- pageX for horizontal mouse position

#part 7

- create button below sliders with document.createElement
- each slider is <input> element with type='range' and min value 0
and max value 25
- functions: createButton, createSlider, addLetter

#part 8

- dont use id's and put everything of part 7 in 1 fucntion and call that
function in part 8, and it works!
