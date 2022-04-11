# Welcome to the Color Guess project repository! 🎨

# Project requirements

### 💡 In this project an RGB color guesser should be implemented. Given an RGB string, 6 visual color alternatives should be presented, one of them the correct color.

---

## Mandatory requirements:

### 1 - The webpage must have a title with the name of the game.

- The title **id** should be `title`.

### 2 - The webpage should contain a text with the RGB code to be guessed.

- The **id** should be `rgb-color`.
- This text must contain the three numbers of the RGB colors, in the following format: `(168, 34, 1)`.

### 3 - The webpage should contain color options to be guessed.

- There should be 6 circles as color guessing options.
- The circles should have the **class** `ball`.

### 4 - The colors of the circles should be generated dinamically.

- When the page is loaded, the the colors of each of the 6 colored circles must be generated via JavaScript.

### 5 - When clicking on a colored circle, a text should be presented indicating if it was the correct choice.

- The element **id** should be `answer`.
- When the game starts, the text displayed should be `"Escolha uma cor"`.
- If the colored circle is **correct**, the text `"Acertou!"` should be displayed.
- If the colored circle is **incorrect**, the text `"Errou! Tente novamente!"` should be displayed.

### 6 - Create a button to start/restart the game.

- The button must have the **id** `reset-game`.
- When clicking the button, new colors must be generated via JavaScript and the `rgb-color` element must be updated.
- Upon clicking the button, the `answer` element should return to its initial state, displaying the text `"Choose a color"`.

## BONUS

### 7 - Create a score that increments 3 points for every hit in the game.

- The element must have the **id** `score`.
- Its initial value must be 0.
- For every hit, 3 points are added to the score.
- By clicking the reset button, the score **MUST NOT** be reset.

---

🚀
