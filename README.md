**Project Title:** Garbage Classification using OpenCV, ORB, and KNN

**Description:**

This project demonstrates the implementation of a real-time garbage classification system using OpenCV, ORB (Oriented FAST and Rotated BRIEF), and KNN (K-Nearest Neighbors) matcher. The system is capable of accurately classifying into paper garbage or plastic grabage based on visual features extracted from images.

**Key Features:**

- **Real-time classification:** The system can process images in real-time, providing immediate feedback on the type of garbage.
- **ORB feature extraction:** The ORB algorithm is used to extract distinctive features from images, making the system robust to changes in lighting and viewpoint.
- **KNN matching:** The K-Nearest Neighbors algorithm is used to classify images based on their similarity to known examples.
- **High accuracy:** The system achieves high accuracy in classifying different types of garbage, thanks to the effective combination of ORB and KNN.

**Dependencies:**

- OpenCV
- NumPy
- Scikit-learn
- Streamlit for GUI

**Installation:**

1. Install the required dependencies using pip:
   ```bash
   pip install opencv-python numpy scikit-learn
   ```

2. Clone this repository or download the project files.

**Usage:**

1. Prepare your dataset of labeled garbage images.
2. Train the KNN classifier using your labeled dataset.
3. Run the script to capture images from your webcam or load images from a directory.
4. The system will process each image, extract features using ORB, and classify it using KNN.
5. The classification result will be displayed.

**Additional Notes:**

- You may need to adjust the parameters of the ORB and KNN algorithms to optimize performance for your specific dataset.
- Consider using a larger dataset and exploring other feature extraction and classification techniques for better accuracy.
- For real-time deployment, you can integrate this system with a web application or a mobile app.


