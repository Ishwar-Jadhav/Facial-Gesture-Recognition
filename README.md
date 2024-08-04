# Facial-Gesture-Recognition
This repository contains code for a facial recognition project that leverages the dlib library for detecting facial landmarks and uses a K-Nearest Neighbors (KNN) classifier to classify faces based on extracted features.

![Screenshot 2024-08-03 at 20 52 22](https://github.com/user-attachments/assets/1e649364-aabe-4551-a875-2906916c9bfa)

Table of Contents

Installation
Usage
Project Structure
Contributing
License
Installation

To get started with this project, you'll need to set up your Python environment and install the required libraries.

Prerequisites
Ensure you have Python 3.x installed. You can check your Python version by running:

bash
Copy code
python --version
Clone the Repository
Clone this repository to your local machine using:

bash
Copy code
git clone https://github.com/your-username/facial-recognition-knn.git
cd facial-recognition-knn
Install Required Libraries
You can install the necessary Python libraries using pip:

bash
Copy code
pip install -r requirements.txt
If you encounter issues with the cv2 library (OpenCV), you can install it separately:

bash
Copy code
pip install opencv-python
Usage

This project is implemented in a Jupyter notebook, and the steps below outline how to use it.

Running the Notebook
Open the Jupyter notebook:
bash
Copy code
jupyter notebook FGR.ipynb
Run the cells in the notebook sequentially. The key steps include:
Importing required libraries (cv2, dlib, pandas, numpy, sklearn).
Loading the face detector and shape predictor from dlib.
Initializing the webcam feed to capture images.
Processing facial landmarks to extract features.
Training a K-Nearest Neighbors (KNN) classifier on the extracted features.
Evaluating the model's performance on test data.
Directory Structure
Dataset/Train/: Directory where training data is stored.
Dataset/Test/: Directory where testing data is stored.
shape_predictor_68_face_landmarks.dat: Pre-trained model file for facial landmark detection (not included, must be downloaded separately).
Example Output
Once the model is trained, it will output the accuracy of the KNN classifier on the test data.

Project Structure

plaintext
Copy code
├── Dataset
│   ├── Train
│   │   ├── Rohan
│   │   └── Ishwar
│   └── Test
│       ├── Rohan
│       └── Ishwar
├── FGR.ipynb
├── requirements.txt
└── README.md
Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs or feature requests.

License

This project is licensed under the MIT License - see the LICENSE file for details.

This README provides an overview of the project and instructions on how to set up and use the code. Adjust the content as necessary to match your project's specific details and structure.
