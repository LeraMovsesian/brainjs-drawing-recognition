# Simple Machine Learning Model with Brain.js

This project is a simple web-based tool that uses [Brain.js](https://brain.js.org/) to train a neural network to recognize happy and sad faces drawn on a canvas.

## Features

- Draw on a canvas using your mouse.
- Label drawings as happy or sad.
- Train a neural network to recognize your drawings.
- Classify new drawings as happy or sad.

## Getting Started

### Prerequisites

- A modern web browser with JavaScript enabled.

### Running the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/LeraMovsesian/brainjs-drawing-recognition.git
    ```
2. Navigate to the project directory:
    ```bash
    cd brainjs-drawing-recognition
    ```
3. Open `index.html` in your web browser.

### Usage

1. **Draw a happy or a sad smile:** Click and drag to draw.
2. **Save Drawing and Train the Neural Network:** Press the `V` key after drawing a smile to train the Neural Network. Confirm if the drawing is happy or sad.
3. **Clear the Canvas:** Press the `C` key and repeat the process drawing different smiles to train the Neural Network.
4. **Classify Drawing:** Press the `B` key after training to classify the current drawing.

## Code Overview

- **HTML:** Includes a canvas element and Brain.js.
- **CSS:** Styles the canvas and background.
- **JavaScript:** Handles drawing, saving training data, training the neural network, and classifying drawings.


