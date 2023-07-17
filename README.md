# Hand Gesture Calculator

This Python script uses computer vision and hand tracking techniques to create a calculator that can be operated through hand gestures. The script allows users to perform mathematical calculations by interacting with virtual buttons using their hand movements.

## Features

- Tracks the user's hand using a webcam.
- Recognizes hand gestures to perform button clicks.
- Displays a virtual calculator interface on the screen.
- Supports basic arithmetic operations: addition, subtraction, multiplication, and division.
- Provides an output field to view the entered equation and the calculated result.

## Dependencies

The following dependencies are required to run the script:

- OpenCV (cv2)
- cvzone
- numpy

You can install the required packages using the following command:


pip install opencv-python cvzone numpy


## Usage

1. Run the Script:
   - Connect a webcam to your computer.
   - Run the Python script.

2. Interact with the Calculator:
   - Hold your hand in front of the webcam.
   - Use your fingers to perform gestures to click the virtual buttons.
   - Move your hand closer or farther to the webcam to clear the equation.

3. Perform Calculations:
   - The calculator recognizes gestures for numbers 0-9, operators (+, -, *, /), decimal point (.), and equals (=).
   - The recognized gestures will update the equation on the screen.
   - The calculated result will be displayed in the output field.

4. Quit the Application:
   - Press the 'c' key on your keyboard to quit the application.

## Demo

[Include a link to a demo video or GIF showcasing the calculator in action.]

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
