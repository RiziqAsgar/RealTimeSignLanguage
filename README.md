# Sign Language Recognition with Face Tracking and Hand Gesture Recognition

This Python project combines real-time sign language recognition, face tracking, and hand gesture recognition using MediaPipe and Pygame. It enables the interpretation of sign language gestures captured by a webcam and produces corresponding audio output. The project also includes an SVM model training module for sign language recognition.

## Features

- Real-time sign language recognition.
- Face tracking using the MediaPipe library.
- Hand gesture recognition for interpreting sign language.
- SVM model training for improved sign language recognition accuracy.
- Audio output for sign language gestures using Pygame.
- Easily customizable for various sign language gestures and audio responses.

## Getting Started

1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Train your own sign language recognition SVM model (optional).
4. Run the main script to start real-time sign language recognition and face tracking.

## Usage

- Use the webcam to capture sign language gestures.
- The program will interpret the gestures and produce corresponding audio output.
- Customize the recognized gestures and audio responses as needed.

## Dependencies

- Python 3.x
- OpenCV
- MediaPipe
- Pygame
- Scikit-learn

## Training Your Own SVM Model

If you want to train your own SVM model for sign language recognition, follow the instructions in the `TRAIN MODEL` section of the code. You can use your own dataset and adapt the model to your specific sign language gestures.

## Dataset Creation

To create a custom sign language recognition dataset:

1. Set up a camera or webcam to capture sign language gestures.
2. Record a variety of sign language gestures with proper lighting and background.
3. Save the captured frames or videos, ensuring each gesture is associated with a corresponding label.

## Model Training

To train your own SVM model for sign language recognition:

1. Prepare your dataset with labeled sign language gestures.
2. Uncomment and modify the code in the `TRAIN MODEL` section of the code to load your dataset and train the SVM model.
3. Experiment with different parameters to optimize model accuracy.
4. Train the model, which will be saved as a `.pkl` file.

## Model Testing

To test the trained SVM model:

1. Ensure the model file (e.g., `huruf.pkl`) is in the same directory as the main script.
2. Run the main script to start real-time sign language recognition and face tracking.
3. Perform sign language gestures in front of the webcam.
4. Observe the program's interpretation of your gestures and the corresponding audio output.

Feel free to modify and expand upon these steps based on your specific dataset and requirements.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [MediaPipe](https://mediapipe.dev/)
- [Pygame](https://www.pygame.org/)
- [Scikit-learn](https://scikit-learn.org/)
- Add any other relevant acknowledgments here.
