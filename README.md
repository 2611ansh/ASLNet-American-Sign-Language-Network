# Sign Language Prediction

This is the README file for the "Sign Language Prediction" project. The project is designed to predict sign language gestures using computer vision techniques.

## Project Repository

You can find the project's code and files in the following GitHub repository:

[Sign Language Prediction GitHub Repository](https://github.com/2611ansh/sign-language-prediction.git)

## Project Overview

The "Sign Language Prediction" project utilizes computer vision technology to recognize sign language gestures. It can be a valuable tool for communication between individuals who use sign language and those who may not be proficient in it. The project includes the following key components:

- Accepting sign language images for prediction.
- Using a trained model to predict the corresponding sign language gesture.
- Displaying the predicted gesture image as a response.

## How to Use

To use the Sign Language Prediction system, follow these steps:

1. Clone the project repository to your local machine:

   ```shell
   git clone https://github.com/2611ansh/sign-language-prediction.git
   ```

2. Ensure you have the required dependencies installed. You can typically install them using `pip`:

   ```shell
   pip install -r requirements.txt
   ```

3. Navigate to the project directory:

   ```shell
   cd sign-language-prediction
   ```

4. Run the Flask application using the following command:

   ```shell
   python app.py
   ```

   The application will start and be accessible at [http://localhost:8080](http://localhost:8080) in your web browser.

5. On the web page, you can either submit an image for prediction or start a live camera feed for real-time sign language recognition.

## Features

- Predict sign language gestures from submitted images.
- Start a live camera feed for real-time sign language recognition.
- Utilize the YOLOv5 model for object detection and gesture prediction.

## Acknowledgments

- OpenCV and YOLOv5 for computer vision capabilities.
- The dataset used for training and testing the sign language gesture recognition model.
- The open-source community for valuable resources and inspiration.

Feel free to reach out for any questions or suggestions related to this project. Happy sign language prediction!
