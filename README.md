# Turtle Alphabet Drawer

This Python script uses the `turtle` graphics library to draw uppercase English letters (A-Z) on the screen based on user input. The script interprets a given string and renders the corresponding letters in a visual format.

## Features

- **Dynamic Letter Drawing**: Draws uppercase English letters based on user input.
- **Customizable Display**: Allows customization of the turtle's speed, color, and starting position.
- **Interactive**: Can accept user input via the terminal or predefined text in the code.

## Requirements

- Python 3.x
- The `turtle` library (pre-installed with Python)

## How to Use

1. Clone or download this repository to your local machine.
2. Run the script using Python:

   ```bash
   python turtle_drawer.py
   ```

3. Enter a string containing uppercase English letters when prompted.
4. Watch the turtle draw each letter sequentially on the screen.

## Customization

- **Letter Size**: Adjust the size of the letters by modifying the scaling factors in the script.
- **Pen Color and Speed**: Customize the `turtle` pen color and speed by modifying the relevant variables.

## Example Usage

If the user inputs the string `"HELLO"`, the turtle will draw each letter of the word `HELLO` on the screen in sequence.

## Code Overview

1. **Letter Coordinates**: Each letter is defined as a series of coordinates and pen movements.
2. **Drawing Function**: The script uses a function to parse the input string and call individual letter-drawing routines.

## Contribution

Contributions are welcome! Feel free to submit issues or pull requests with suggestions for improvements or new features.
