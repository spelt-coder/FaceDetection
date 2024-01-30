# Face Detection

## Group: Visionary Angels

### Description: Comparison of Face Detection Techniques 

This repository illustrates implementations of five face detection techniques using different libraries. The goal is to compare the effectiveness of these techniques in spotting faces in images.

### Implemented Techniques:

1. **OpenCV with Haar Cascade:**
   - Utilizes OpenCV and Haar Cascade classifier for face detection.
   - Draws rectangles around detected faces.

2. **OpenCV with DNN:**
   - Implements face detection using OpenCV's deep neural network (DNN) module.
   - Utilizes a pre-trained model for accurate face detection.
   - Draws rectangles around the detected faces with confidence filtering.

3. **Dlib with CNN:**
   - Utilizes Dlib library with a Convolutional Neural Network (CNN) face detection model.
   - Draws rectangles around the faces detected in the image.

4. **Dlib with HoG and Linear SVM:**
   - Implements face detection using Dlib with Histogram of Oriented Gradients (HoG) and linear Support Vector Machine (SVM).
   - Draws rectangles around detected faces.

5. **MTCNN (Multi-task Cascaded Convolutional Networks):**
   - Implements face detection using MTCNN, a robust multi-task model.
   - Draws rectangles around detected faces with bounding box coordinates.

Each method is implemented in its own Jupyter cell.

### File Structure:

- `opencv_haarcascade/`: Contains Haar Cascade classifier XML file for OpenCV Haar Cascade implementation.
- `opencv_dnn/`: Includes files for OpenCV DNN face detection model.
- `dlib_cnn/`: Contains the Dlib CNN face detection model file.
- `imgs/`: Contains sample images for testing face detection techniques.

