# Interactive Regression Visualizer

This is a web-based tool that uses your webcam to intuitively explore the concept of a regression coefficient (β) in real-time.

![Interactive Regression Visualizer in action](https://placehold.co/600x400/111827/ffffff?text=App+Screenshot+Here)

## Features

- **Live Hand Tracking:** Uses your hands to control the slope of a regression line.
- **Real-time Coefficient Calculation:** See the `β` value change instantly as you move your hands.
- **Interactive Data:** Visualize a scatter plot of data points that adjusts to the line.
- **Variable Scaling:** Change the scale of the X and Y axes (`0-10`, `0-100`, etc.) to see how it impacts the coefficient.
- **Precision Control:** Adjust a slider to see how the tightness (precision) of the data affects your model.

## How to Use

1.  **Open the link** to the application.
2.  **Allow camera access** when prompted by your browser.
3.  **Clap and show both hands** to the camera to begin.
4.  Move your hands to change the slope and use the on-screen controls to explore!

## Development

This application was created with the help of Google's Gemini Pro. The core functionality is built with standard HTML, JavaScript, and CSS, using the [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) library for hand tracking. Inspired by [this](https://x.com/googleaidevs/status/1936193938639012065) X thread 21st June 2025. 

## Feedback

Feedback, questions, and suggestions are welcome. Please contact [david.bann@ucl.ac.uk](mailto:david.bann@ucl.ac.uk). 

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
