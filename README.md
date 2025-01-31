# Face Emotion Recognition using GoogleNet and ONNX

## Overview
This project employs the **GoogleNet Deep Learning Architecture** in an ONNX model that has been pre-trained with our custom dataset to recognize human emotions based on facial expressions. By leveraging OpenCV for image processing and Python libraries such as NumPy and Matplotlib, the system detects faces and predicts corresponding emotions with high accuracy.

## Features
- **GoogleNet-based ONNX Model**: Utilizes the power of GoogleNet for efficient and accurate emotion classification.
- **Face Detection**: Uses OpenCV's Haar Cascade to detect faces in images.
- **Emotion Recognition**: Predicts emotions such as happiness, anger, sadness, and surprise.
- **Image Processing**: Preprocessing techniques including grayscale conversion and resizing for optimized model performance.
- **Multi-Face Detection**: Supports detection and classification of multiple faces within an image.

## Project Workflow
1. **Pretrained GoogleNet ONNX Model**: A custom dataset is used to fine-tune GoogleNet for emotion classification.
2. **Image Preprocessing**: The input image is resized and converted to a suitable format for the model.
3. **Face Detection**: OpenCV detects faces in the image before passing them to the model.
4. **Emotion Prediction**: The detected faces are processed and classified into different emotional states.
5. **Output Display**: The recognized emotions are displayed on the image.

## Technologies Used
- **GoogleNet (Inception v1)**: A deep learning architecture optimized for feature extraction and classification.
- **ONNX Runtime**: Ensures compatibility across various platforms.
- **OpenCV**: For face detection and image preprocessing.
- **Python Libraries**: NumPy, PIL, Matplotlib for data processing and visualization.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/face-emotion-recognition.git
   cd face-emotion-recognition
   ```
2. Install dependencies:
   ```sh
   pip install onnxruntime opencv-python-headless pillow numpy matplotlib
   ```
3. Run the emotion recognition script:
   ```sh
   python recognize_emotion.py
   ```

## Applications
- **Human-Computer Interaction (HCI)**: Enhancing interactive experiences.
- **Mental Health Monitoring**: Analyzing facial expressions for early detection of emotional distress.
- **Security and Surveillance**: Detecting suspicious behavior based on emotions.
- **Education & Marketing**: Understanding user engagement and reactions.

## Future Enhancements
- Integration with real-time video streams.
- Expansion of the emotion dataset for improved accuracy.
- Deployment as a web or mobile application.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Chaithanya Nadithoka
