# ColorPicker Component
A simple and interactive color picker built with React, allowing users to select and preview colors in real-time.

## Features
- **Live Color Preview**: Displays the selected color in a background area, updating in real-time as the user picks a new color.
- **Color Input Field**: Includes a color input field that allows users to select any color using a native color picker.

## Code Overview
The component uses React's `useState` hook to manage the selected color state. It updates the displayed color in real-time when the user picks a new one.

## Core Logic
- **`color`**: State variable that holds the currently selected color. Default set to `#FFFFF`.
- **`handleColorChange(event)`**: Updates the color state whenever a new color is chosen by the user from the color input field.
