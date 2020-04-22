# Smart Drop-down List

Drop-down lists are nice. What's nicer is when ultra-long lists can be *searchable*. For this, we first need a standard drop-down list. And then some HTML, CSS and JavaScript.

## HTML
- A div encapsulating all elements, including the initial drop-down list.
- A text box.
- A div dressed up to look like a button.
- An onrdered list, empty.

## CSS
- Most of this is purely decorative and layout.
- The `select` tag is hidden.

## JavaScript
- When the "button" is clicked, populate the unordered list with text from the drop-down list, and display the unordered list.
- On clicking the items, the text should be reflected in the text box and the unordered list should be hidden again.
- When text is entered in the text box, iterate through all the items in the drop-down list and add *only* the items that contain the text in the text box, then display the unordered list.
- Again, on clicking the items, the text should be reflected in the text box and the unordered list should be hidden again.
