# Audio-visualizer

# Microphone Audio Visualization with Animated Balls

This project demonstrates how to create a simple audio visualization using the microphone input and animated balls. It uses the Web Audio API to capture audio from the user's microphone and creates bouncing balls on an HTML5 canvas that react to the audio input.

## Prerequisites

Before running the project, make sure you have the following:

- A modern web browser that supports the Web Audio API.
- A web server to serve the HTML and JavaScript files if you are not testing locally.

## Getting Started

1. Clone this repository to your local machine:

   \\ bash
   git clone https://github.com/nugmara/Audio-visualizer.git
   \\

2. Open the `index.html` file in your web browser or serve it using a web server.

3. You will be prompted to grant microphone access. Allow access to start visualizing the audio.

## How It Works

The project consists of two main components:

\\\javascript
// Microphone Class: The Microphone class initializes the microphone, captures audio data,
// and provides methods to get audio samples and volume. It uses the Web Audio API to set up audio processing.
class Microphone {
   // ... Microphone class code here ...
}

// Bouncing Balls: The Ball class represents individual bouncing balls on the canvas.
// Balls react to the audio input by falling and jumping based on the volume of the microphone input.
class Ball {
   // ... Ball class code here ...
}
\\\

## Customization

You can customize the project by adjusting the following:

- Change the canvas size by modifying the `canvas.width` and `canvas.height` values in the JavaScript code.
- Adjust the ball properties such as radius, colors, jump force, and fall force in the `Ball` class.
- Modify the behavior of the balls based on audio input in the `animate` function.


