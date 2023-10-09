# MATLAB GUI Eye and Face Detection App

This repository contains a MATLAB GUI application that uses image processing techniques to detect and track facial features such as eyes, mouth, and nose. The app is capable of detecting eye open/close events and providing alerts when the eyes are closed.





## Features

- **Face Detection**: The application uses a pre-trained model to detect and locate faces in the input image or video stream.
- **Eye Detection**: The app identifies and highlights the eyes within the detected face region.
- **Mouth Detection**: Mouth detection is implemented to locate the mouth within the detected face region.
- **Nose Detection**: The application also detects and highlights the nose within the detected face region.
- **Eye Open/Close Detection**: The app continuously monitors the eyes and provides alerts if they are closed for a specified duration.

## How to Use

1. Clone or download this repository to your local machine.

2. Open MATLAB and navigate to the directory where the repository is located.

3. Run the MATLAB script `main.m` to start the application.

4. Load an image or video using the provided options in the application.

5. The application will display the detected face, eyes, mouth, and nose, along with tracking eye open/close events.

6. If the eyes are closed for the specified duration, an alert will be triggered.

## Dependencies

Ensure you have the following dependencies installed:

- MATLAB R2018b or later
- Image Processing Toolbox



## Contributing

Contributions are welcome! If you have any ideas for improvements, enhancements, or bug fixes, please open an issue or create a pull request.



