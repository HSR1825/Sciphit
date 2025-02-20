# SciPhit: Gesture-Based Communication System

## Overview
SciPhit is an advanced sign language detection system that utilizes deep learning and computer vision techniques to interpret human gestures for communication. It is primarily designed to assist visually and speech-impaired individuals in expressing themselves effectively.

## Features
- **Real-Time Gesture Recognition**: Detects and interprets hand and body movements.
- **Deep Learning Integration**: Utilizes LSTM-based neural networks for action recognition.
- **User-Friendly Interface**: Provides a seamless and interactive experience.
- **Assistive Communication**: Designed to help individuals with speech and visual impairments.
- **Real-Time Video Processing**: Uses OpenCV for live gesture recognition.

## Technologies Used
- **Python** - Core programming language for implementation.
- **TensorFlow & Keras** - Machine learning frameworks for training and recognition.
- **MediaPipe** - Used for real-time hand tracking and gesture recognition.
- **OpenCV** - Image processing and computer vision tasks.
- **Matplotlib** - For visualization of processed gestures.
- **scikit-learn** - For data processing and evaluation.

## Installation
### Prerequisites
Ensure you have Python installed (Recommended version: Python 3.7+)

### Steps to Install
1. Clone the repository:
   ```sh
   git clone https://github.com/Gupta-4388/sciphit.git
   cd sciphit
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```sh
   python sciphit.py
   ```
2. The system will start detecting hand and body gestures in real-time.
3. Use predefined gestures to communicate, and the system will interpret them live.

## Dataset & Model Training
- The model is trained using a dataset containing multiple human gestures.
- Uses LSTM-based neural networks for accurate gesture classification.
- Keypoints are extracted using MediaPipe's holistic pipelines and stored for training.

## Future Enhancements
- Support for additional gestures and languages.
- Integration with speech synthesis for spoken output.
- Improved accuracy using advanced deep learning models.
- Mobile and web-based application versions.

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For inquiries or collaboration, contact:
- **Your Name**: [lakshminarayanaguptaboddu@gmail.com]
- **GitHub**: [https://github.com/Gupta-4388/sciphit]