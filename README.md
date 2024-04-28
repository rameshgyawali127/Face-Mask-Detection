Face Mask Detection

Table of Contents
Introduction
Installation
Usage
Dependencies
Contributing
License
Introduction
This project aims to detect whether a person is wearing a face mask or not using computer vision and deep learning techniques. It provides functionality to detect masks both on static images and through webcam streams. The project is implemented in Python using TensorFlow, OpenCV, and Streamlit.

Installation
To install the required dependencies, run the following command:

bash
Copy code
pip install -r requirements.txt
Usage
Running the Application
To run the face mask detection application, execute the following command:

bash
Copy code
streamlit run app.py
The application will open in your default web browser.

Detection Modes
The application supports two modes of detection:

Image: Upload an image to detect face masks.
Webcam: Use your webcam to detect face masks in real-time.
Dependencies
This project relies on the following libraries:

TensorFlow
Keras
OpenCV
NumPy
Matplotlib
Imutils
Pillow
Streamlit
Onnx
Tf2onnx
For a complete list of dependencies and their versions, refer to the requirements.txt file.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository
Create your feature branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -am 'Add some feature')
Push to the branch (git push origin feature/YourFeature)
Create a new Pull Request
License
This project is licensed under the MIT License.
